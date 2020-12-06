# ansible-role-bastille
Ansible role for bastille containers in Freebsd.

## Usages
```
$ cat bastille.yml
---
# this playbook will install bastille pkg,
# template, create some bastille container
# and in that container it will install
# some template
- hosts: localhost
  become: yes
  gather_facts: yes

  tasks:
    - import_role:
        name: ansible-role-bastille
$
```
