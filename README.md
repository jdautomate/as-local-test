# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* Access Server Test VM - Local using vagrant, ansible and virtualbox
* AS 2.1.9

### Where to start? ###

* Dependencies are ansible, vagrant and virtualbox on your local machine

* Clone the repo with git@bitbucket.org:jdopenvpn/as-local-test.git
* chmod +x setup.sh
* run ./setup.sh (script will create and start the VM, replace Vagrantfile, apt-get update and install python - necessary for ansible) 
* run ./vagrant.sh

The playbook will take a bit to run, it has to download and install AS, after that is done the tests are fast.  Results can be seen in the textfile -
/tmp/results.txt (on your local machine)

vagrant destroy runs to wipe out the VM once the test is done.

That is it.
