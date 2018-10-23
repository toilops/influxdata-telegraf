Influxdata Telegraf
=========

Ansible role to install and manage the InfluxData Telegraf metric and data daemon

Requirements
------------

No requirements at this time.

Role Variables
--------------

This role currently has the following variables that can be overridden within your playbook.

```yaml
telegraf_name: telegraf # Package name to install
telegraf_version: latest # Version of the influxDB to install.
```

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Example on how to include this role into your playbook.

    - hosts: servers
      tasks:
        - name: Install Telegraf
          include_role:
            name: toilops.influxdata_telegraf
          vars:
            telegraf_version: telegraf-1.8.2-1

License
-------

MIT

Author Information
------------------

Find me on github [@BondAnthony](https://github.com/BondAnthony)
