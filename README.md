Ansible playbook to deploy an Ansible control server
=========================================================

Requirements
------------

Ubuntu 14.04LTS server hosted as provided by AWS.

[Ansible](http://ansible.com) 1.9 or higher must be installed.  The easiest way
is to use Pip:

```bash
pip install ansible
```

Inventory
---------

You must provide an inventory file with the name of your control server.

```bash
echo control.mydomain.com > inventory
```

Deploy Ansible
--------------

```bash
ansible-playbook site.yml
```
