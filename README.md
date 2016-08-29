Role Name
=========
gwenlei.rails-monit

Requirements
------------
ubuntu16.04 xenial

Role Variables
--------------
defaults/main.yml

app_name: demo
monit_time: 60

Dependencies
------------
none

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: gwenlei.rails-monit }

License
-------
MIT

Author Information
------------------
onecloud
