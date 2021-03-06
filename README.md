# Ansible Collection - aramirol.linux

[![Galaxy version](https://img.shields.io/badge/dynamic/json?style=flat&label=galaxy&logo=ansible&url=https://galaxy.ansible.com/api/v2/collections/aramirol/linux/&query=latest_version.version)](https://galaxy.ansible.com/aramirol/linux)
[![Licence](https://img.shields.io/github/license/aramirol/ansible-collection-linux?logo=license)](https://github.com/aramirol/ansible-collection-linux/blob/main/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/aramirol/ansible-collection-linux?logo=github)](https://github.com/aramirol/ansible-collection-linux/commits/main)

## Tested with Ansible
Tested with Ansible 2.10.x

## Dependencies
```yml
collections:
  - name: community.general
  - name: community.docker
```

## Included content
### Roles

| FQDN Name | Documentation | Build Status |
| --------- | :-----------: | :----------: |
| aramirol.linux.docker | [Readme](https://github.com/aramirol/ansible-collection-linux/blob/main/roles/docker/README.md) | [![](https://img.shields.io/github/workflow/status/aramirol/ansible-collection-linux/docker/main?logo=github)](https://github.com/aramirol/ansible-collection-linux/actions/workflows/role_docker.yaml?query=branch%3Amain) |
| aramirol.linux.epel | [Readme](https://github.com/aramirol/ansible-collection-linux/blob/main/roles/epel/README.md) | [![](https://img.shields.io/github/workflow/status/aramirol/ansible-collection-linux/epel/main?logo=github)](https://github.com/aramirol/ansible-collection-linux/actions/workflows/role_epel.yaml?query=branch%3Amain) |
| aramirol.linux.lxd | [Readme](https://github.com/aramirol/ansible-collection-linux/blob/main/roles/lxd/README.md) | [![](https://img.shields.io/github/workflow/status/aramirol/ansible-collection-linux/lxd/main?logo=github)](https://github.com/aramirol/ansible-collection-linux/actions/workflows/role_lxd.yaml?query=branch%3Amain) |
| aramirol.linux.users | [Readme](https://github.com/aramirol/ansible-collection-linux/blob/main/roles/users/README.md) | [![](https://img.shields.io/github/workflow/status/aramirol/ansible-collection-linux/users/main?logo=github)](https://github.com/aramirol/ansible-collection-linux/actions/workflows/role_users.yaml?query=branch%3Amain) |

## Using this collection
Before using the collection, you need to install the collection with the `ansible-galaxy` CLI:

```shell
ansible-galaxy collection install aramirol.linux
```

You can also include it in a `requirements.yml` file and install it via:

```shell
ansible-galaxy collection install -r requirements.yml
```

Using the format:

```yaml
collections:
  - aramirol.linux
```

See [Ansible Using collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html) for more details.

## Licensing
GNU General Public License v3.0 or later

See [LICENSE](https://github.com/aramirol/ansible-collection-linux/blob/main/LICENSE) to see the full text.

