environment
===========

Ansible role which helps to configure environment variables.


Example
-------

```
---

# Example how to use the role
- hosts: myhost
  vars:
    environment_config:
      http_proxy: http://proxy.example.com:3128
      https_proxy: http://proxy.example.com:3128
  roles:
    - environment
```


Role variables
--------------

List of variables used by the role:

```
# Default environment file
environment_file: /etc/environment

# Default set of environment variables
environment_config: {}
```


License
-------

MIT


Author
------

Jiri Tyr
