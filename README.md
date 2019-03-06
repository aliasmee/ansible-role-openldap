Ansible Role: Openldap
=========

Quick install openldap using ansible.

`Idempotent operations are not supported for the time being`

Requirements
------------

* ansible 2.4+
* centos7+

Role Variables
--------------

variables_name | Description | Default
--- | --- | ---
`ldap_manager_passwd` | ldap super manager passwd (User:Manager) | `iamaPassDw24iH`
`ldap_olcsuffix` | ldap base dn | `dc=example,dc=com`
`ldap_o` | ... | 'example com'
`o` | ... | 'example'

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role :

```yml
---
- hosts: my-vpn
  remote_user: root
  roles:
    - ansible-role-openldap
```

License
-------

MIT

Author Information
------------------

@aliasmee
