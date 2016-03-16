ansible-role-nodejs-osx
=======================

This ansible role will install Node.js via homebrew.

Requirements
------------

This Ansible role requires homebrew to be installed.

Role Variables
--------------

The only role variable is the homebrew version to install.

```
nodejs_version: node
```

Dependencies
------------

This Ansible role requires homebrew to be installed.

Example Playbook
----------------

Here's a short example of this role in action.

```
    - hosts: servers
      roles:
         - role: nodejs
           nodejs_version: node
```

License
-------

BSD

Author Information
------------------

[JP Grace](https://github.com/jpgrace)