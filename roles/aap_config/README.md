# Role Name

A brief description of what this role does.

## Requirements

* List any prerequisites here (e.g., specific OS versions, Python packages, or hardware requirements).
* If none, state: "None."

## Role Variables

| Variable Name | Default Value | Description |
|---|---|---|
| `my_role_port` | `8080` | The port the service binds to. |
| `my_role_enabled` | `true` | Controls whether the service starts automatically. |

## Dependencies

* List any dependency roles here (from Galaxy/Automation Hub).
* If none, state: "None."

## Example Playbook

```yaml
---
- name: Use this role
  hosts: all
  become: true
  vars:
    my_role_port: 9000
  roles:
    - role: tigbit.aap_config.my_role_name
```

## License

BSD / MIT / GPL-3.0-or-later

## Author Information

Created by **Your Name** (tigbit)

