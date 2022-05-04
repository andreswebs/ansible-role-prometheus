# ansible-role-prometheus

Ansible role to install Prometheus.

## Requirements

The `jq` program must be installed on the host. See the
[jq web page](https://stedolan.github.io/jq/) to install.

## Install

```sh
ansible-galaxy install andreswebs.prometheus
```

## Example Playbook

```yaml
---
- hosts: servers
  roles:
    - role: andreswebs.prometheus
```

## Authors

**Andre Silva** [@andreswebs](https://github.com/andreswebs)

## License

This project is licensed under the [Unlicense](UNLICENSE.md).
