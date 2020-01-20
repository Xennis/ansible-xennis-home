# Ansible Playbook: OctoPrint on a Raspberry PI (OctoPI)

[![Build Status](https://travis-ci.org/Xennis/xennis-octopi.svg?branch=master)](https://travis-ci.org/Xennis/xennis-octopi)

### Initial local setup

Add a `[octopi]` group to `/etc/ansible/hosts` with the IP of the Pi.

### Setup the Raspberry PI

Requirements:
* Ansible is installed
* Pi with OctoPrint is up and running

Run the playbook
```sh
ansible-playbook xennis-octopi.yml --ask-become-pass
```
