pip
=========

Installs and configures pip for the user.

Requirements
------------

This role has no requirements. To include this role in your `requirements.txt` file, add the following list item:

```yaml
---
roles:
  - name: whalej84.pip
    src: https://github.com/WhaleJ84/ansible-role-pip.git
    scm: git
```

Example Playbook
----------------

This example playbook shows how I would use this role, with custom variables to suit my needs.

```yaml
---
- hosts: localhost

  roles:
    - role: whalej84.pip
      tags: [ pip ]
```

