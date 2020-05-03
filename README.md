# Ansible Playbook: OctoPrint on a Raspberry Pi (OctoPi)

[![Build Status](https://travis-ci.org/Xennis/xennis-octopi.svg?branch=master)](https://travis-ci.org/Xennis/xennis-octopi)

### Setup the Raspberry Pi

Requirements:
* Ansible is installed
* Pi with OctoPrint is up and running

Run the playbook
```sh
ansible-playbook xennis-octopi.yml --inventory hosts --ask-become-pass
```
