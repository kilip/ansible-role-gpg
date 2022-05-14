Ansible Role: Zeus
=========
Installs and Configure Zeus Workstations.

[![CI](https://github.com/kilip/ansible-role-gpg/workflows/CI/badge.svg?event=push)](https://github.com/kilip/ansible-role-gpg/actions?query=workflow%3ACI)

Requirements
------------
None

Role Variables
--------------
```yaml
gpg_user: "root"
gpg_group: "{{ gpg_user }}"
gpg_key_id: null
gpg_private_key: null
gpg_import_file: "{{ gpg_key_id }}"
gpg_temp_dir: "tmp/gpg"
```

Dependencies
------------
None

Example Playbook
----------------
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: workstation
      roles:
         - role: kilip.zeus

License
-------
MIT

Author Information
------------------
This role was created in 2022 by [Anthonius Munthi](https://itstoni.com)
