Fetch files
=========

Realizes the download of files on a server

Requirements
------------

None

Role Variables
--------------

Is required: vars/paths.yaml

```yaml
  paths:
  name_path_1:
    src: /location/get/file
    dest: /host/location/save/file
    logs_name: [ name_file_1, name_file_2 ]
  name_path_2:
    src: /other/location/get/file
    dest: /host/location/save/file
    logs_name: [ other_name_file_1, other_name_file_2 ]
```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
  - hosts: servers
    roles:
        - { role: get-file }
```

License
-------

GNU General Public License v3.0

Author Information
------------------

Antonio Cleverson dos Santos \<cleverson.developer@gmail.com\>
