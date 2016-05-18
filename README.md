Role Name
=========

Installs Kibana on your Ubuntu trusty server

Requirements
------------

Nothing special

Role Variables
--------------

The following variables can be set, and have the shown default values:
```yaml
kibana_server_host: "localhost"
kibana_server_port: 5601
kibana_elasticsearch_url: "http://localhost:9200"
```

Dependencies
------------

Requires java 8 to be installed on the server.
Depends on `nover.java8` to accomplish this

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: nover.kibana }
      vars_files:
         - vars/kibana.yml

With `vars/kibana.yml` setting your overrides for the default values
License
-------

Github The Unlicense

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
