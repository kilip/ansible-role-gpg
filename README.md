Ansible Role: gpg
=========
Ansible role to import gpg key backups

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/kilip/ansible-role-gpg/.github/workflows/testing.yml?branch=main&style=flat-square)](https://github.com/kilip/ansible-role-gpg/actions/workflows/testing.yml)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/kilip/ansible-role-gpg?style=flat-square)](https://github.com/kilip/ansible-role-gpg/releases)
[![GitHub](https://img.shields.io/github/license/kilip/ansible-role-gpg?style=flat-square)](https://github.com/kilip/ansible-role-gpg/blob/main/LICENSE)

Requirements
------------

Export your existing key with this command:
```sh
$ gpg -o backup.gpg --export-options backup --export-secret-keys your.gpg@email.com

```

Role Variables
--------------

None

Dependencies
------------

Define dependencies here

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: gpg }

License
-------

MIT

Author Information
------------------

This role was created in 2023 by [Anthonius Munthi](https://itstoni.com).
