# ansible-role-bastille
Ansible role for bastille containers in Freebsd.

## Usages
```
$ cat bastille.yml
---
# This role will install bastille pkg, template,
# create some bastille containers.
# Then in those containers it will install some templates.
- hosts: localhost
  become: yes
  gather_facts: yes

  tasks:
    - import_role:
        name: ansible-role-bastille
$
```
