# Ansible Role: my_module_file_create

## Description

Easy creation of a file with content

## Requirements

- Ansible >= 2.18 (It might work on previous versions, but we cannot guarantee it)
- Debian and python on deployer machine.
- Python >=3.10

## Role Variables

## Example

### Playbook

```yaml
- name: Module testing
  hosts: localhost
  tasks:

  - name: Create file with context
    my_own_module:
      path: './README.md'
      content: "Home Work NETOLOGY"
```

## License

This project is licensed under MIT License. See [LICENSE](/LICENSE) for more details.

