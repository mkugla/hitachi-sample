Hitachi Sample VM
==============

## Prerequisites
* Install [Vagrant](https://www.vagrantup.com/downloads.html), [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/index.html) and [VirtualBox](https://www.virtualbox.org/wiki/Downloads)


## Usage
* **Step 1**: Clone/Download this repository and change directory to that folder with CLI

* **Step 2**: Using CLI, run the command
```
vagrant up
```
* **Step 3**: After the configuration process ends, you should have access to Cockpit using the information provided below

## Cockpit Access
* URL: https://cockpit.kugla.io
* User: vagrant
* Password: vagrant

## Disclaimer

The used role for Nginx configuration was created only for this single use case.
It wasn't meant to be used in any other projects and scaled to more hosts.
