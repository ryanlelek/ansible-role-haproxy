HAProxy
=======

Installs and configures HAProxy

Requirements
------------

None

Role Variables
--------------

- **haproxy_stats**:          false
- **haproxy_stats_port**:     1234
- **haproxy_stats_uri**:      /haproxy
- **haproxy_stats_users**:
    - { username: username, password: password }

Dependencies
------------

None

Example Playbook
----------------

    - hosts: loadbalancers
      become: yes
      roles:
        - ryanlelek.haproxy

License
-------

MIT

Author Information
------------------

Created by [Ryan Lelek](https://www.ryanlelek.com)  
Part of [AnsibleTutorials.com](http://www.ansibletutorials.com)
