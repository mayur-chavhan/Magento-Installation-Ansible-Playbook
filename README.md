# Magento 2 Ansible Playbook

This is an Ansible Playbook for Magento 2. It is used to set up a quick developer environment on a server.

```
**This is not recommended for production.**
```
I made this playbook to create your own Developer Magento 2 Setup.

Magento 2 installation with Nginx, MariaDB, and PHP.

## Author
* Mayur Chavhan

## Requirements

* Ubuntu 18.04 / 20.04 / 21.04 & Debian 10 or similar debian environment
* Minimum 2GB RAM
* Root user access
* Magento access keys

## Installation

Update the values in:

* hosts
* group_vars/all.yml

Then after editing, run:

```sh

ansible-playbook -i hosts site.yml

```

## More improvement ideas

* [ ] Add sample data using composer auth file.
* [ ] Deploy better security based Nginx VHOST
* [ ] Better PHP-FPM Implementation
* [ ] Set up magento_umask.
* [ ] Select version of Magento
