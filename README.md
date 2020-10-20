# Ansible Playbook: Xennis Home

[![Ansible](https://github.com/Xennis/ansible-xennis-home/workflows/Ansible/badge.svg?branch=master&event=push)](https://github.com/Xennis/ansible-xennis-home/actions?query=workflow%3AAnsible+event%3Apush+branch%3Amaster)

### Usage

Requirements:
* Ansible is installed
* Pi `octopi.local` with OctoPrint is up and running
* Pi `raspotify.local` with Raspbian is up and running

Run the playbook
```sh
ansible-playbook xennis-home.yml --inventory hosts --ask-become-pass
```
