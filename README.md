# Ansible-Role: acr-ansible-create-users

AIT-CyberRange: Creates users


## Requirements

- Debian or Ubuntu 

## Role Variables

```yaml
user_list: []

```

## Example Playbook

```yaml
- hosts: all
  roles:
    - acr-ansible-create-users
      vars:
        user_list: "{{ users }}"
```

## License

GPL-3.0

## Author

- Lenhard Reuter