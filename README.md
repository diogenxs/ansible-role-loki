Role Name
=========

Deploy and configure [Loki/Promtail](https://github.com/grafana/loki) using Ansible.

This is a fork of a simple and extremely useful diogenxs.loki role.

Requirements
------------

- Ansible >= 3.0

Example Playbook
------------

Install Loki and Promtail in local machine

```yml
  - hosts: servers
    roles:
        - role: diogenxs.loki
          vars:
            loki_bins: ['loki', 'promtail'] }
```

License
-------

WTFPL see [LICENSE](license)

Author Information
------------------

Fork maintainer: [weakcamel](https://galaxy.ansible.com/weakcamel)

Original author (all credits due): https://diogenxs.dev
