[![Build Status](https://travis-ci.org/wtanaka/ansible-role-oracle-java.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-oracle-java)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-oracle-java.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-oracle-java)

wtanaka.oracle-java
===================

Ansible role to install oracle-java

Example Playbook
----------------

    - hosts: all
      roles:
         - role: wtanaka.oracle-java
           package_name: oracle-java8-installer

### `package_name`

Default: oracle-java8-installer

The string name of the package to install

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)


License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
