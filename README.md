# Ansible Playbook: OctoPrint on a Raspberry PI (OctoPI)

### Initial local setup

Add a `[octopi]`  to `/etc/ansible/hosts` with the IP of the Pi.

### Setup the Raspberry PI

Requirements:
* Ansible is installed
* PI with OctoPrint is up and running

Run the playbook
```sh
ansible-playbook xennis-octopi.yml --ask-become-pass
```
