# Ansible Playbook: Xennis Home

[![Build Status](https://travis-ci.org/Xennis/xennis-ansible-home.svg?branch=master)](https://travis-ci.org/Xennis/xennis-ansible-home)

### Usage

Requirements:
* Ansible is installed
* Pi `octopi.local` with OctoPrint is up and running
* Pi `raspotify.local` with Raspbian is up and running

Run the playbook
```sh
ansible-playbook xennis-home.yml --inventory hosts --ask-become-pass
```
