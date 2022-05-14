Ansible Role: GPG
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
gpg_key_file: "{{ gpg_key_id }}.key"
gpg_backup_dir: "files/gpg"
gpg_backup_file: "{{ gpg_backup_dir }}/{{ gpg_key_file }}"

github_username: ""
github_token: ""
github_key_id: ""
github_rest_url: "https://api.github.com/user/gpg_keys"
```

Dependencies
------------
None

Example Playbook
----------------
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: workstation
      roles:
         - role: kilip.gpg

License
-------
MIT

Author Information
------------------
This role was created in 2022 by [Anthonius Munthi](https://itstoni.com)
