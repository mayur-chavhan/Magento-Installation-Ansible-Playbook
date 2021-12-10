# :diamond_shape_with_a_dot_inside: Install Magento 2 using Ansible Playbook

This is an Ansible Playbook for Magento 2. It is used to set up a quick developer environment on a server.


## :book: Author
* Mayur Chavhan

<hr />

> **WARNING**: This is not recommended for production.
<hr />
I made this playbook to create your own Developer Magento 2 Setup.


## :wrench: Requirements

* Ubuntu 18.04 / 20.04 / 21.04 & Debian 10 or similar debian environment
* Required Magento Access Keys
  >https://devdocs.magento.com/guides/v2.4/install-gde/prereq/connect-auth.html
* Linux CLI Knowledge

## :cake: Roles
- Composer
- geerlingguy Elasticsearch
- geerlingguy Java
- geerlingguy PHP
- geerlingguy PHP-Versions
- geerlingguy Redis
- Magento
- MariaDB
- Nginx
- PHP
- Python3

## :construction_worker: Installation

Update the values in:

* hosts
* group_vars/all.yml

Then after editing, run:

```bash

ansible-playbook -i hosts install-magento.yml
```

## :crown: Thank you for Jeff Geerling for awesome playbook roles


> https://github.com/geerlingguy


## :rocket: More improvement ideas

* [ ] Add sample data using composer auth file.
* [ ] Deploy better security based Nginx VHOST
* [ ] Better PHP-FPM Implementation
* [ ] Set up magento_umask.
* [ ] Select version of Magento

<hr />

> :star: This repository if you like it.

> :heart: Support Open Source and Free Softwares