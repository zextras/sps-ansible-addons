# Ansible Collection - `zxbot.sps_ansible_addons`

A collection of reusable Ansible addons, plugins, and helpers maintained by Zextras.

The goal of this collection is to provide reusable extensions that can be shared across different Ansible projects. New plugins and helpers will be added over time.

## Installation

Install the latest version from Ansible Galaxy:

```bash
ansible-galaxy collection install zxbot.sps_ansible_addons
```

Install a specific version:

```bash
ansible-galaxy collection install zxbot.sps_ansible_addons:==<version>
```

## Included plugins

| Plugin | Type | Description |
|--------|------|-------------|
| `fqdn_check` | Test plugin | Validates that a value is a valid fully qualified domain name (FQDN). |

## License

GPL-3.0-only