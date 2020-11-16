redis
=====

Install redis-server packages

Role Variables
--------------

```yaml
redis_pass: REDIS_CONNECTION_PASSWORD # Optional. If set you need to authenticate before connecting to redis server.
```

Dependencies
------------

- pylabs.sysbase

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - role: pylabs.redis
  vars:
    redis_pass: connectionpa$$
```

License
-------

MIT

Author Information
------------------

William Wu
