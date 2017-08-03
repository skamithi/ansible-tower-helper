# Tower Organization Role

Given a list of Tower organizations in YAML format, this role creates the Tower organizations. Only Tower superusers can create Tower organizations.

## Requirements

* [ansible-tower-cli](https://github.com/ansible/tower-cli)
* Ansible 2.3+

Role Variables
--------------

* ``tower_orgs``: Define a array of hashes. Each hash has 2 attributes, a ``name`` and ``description``. Example:

```
tower_orgs:
  - name: linuxsimba
    description: "Linuxsimba Org"
```

## Dependencies

None

## Example Playbook

```
    - hosts: localhost
      connection: local
      roles:
         - role: tower-org

```

## License
MIT

## Author Information

Stanley Karunditu [@skamithik](https://twitter.com/skamithik)
