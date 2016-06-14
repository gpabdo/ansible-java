Role Name
=========



Install
------------
Create requirements.yml and add:
```
# java jdk role
- src: https://github.com/gpabdo/ansible-java.git
  version: master
  name: java
```

```
ansible-galaxy install -r requirements.yml
```

Requirements
------------



Role Variables
--------------



Dependencies
------------



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------


