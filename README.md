# Ansible Collection - aramirol.linux

[![Galaxy version](https://img.shields.io/badge/dynamic/json?style=flat&label=galaxy&logo=ansible&url=https://galaxy.ansible.com/api/v2/collections/aramirol/linux/&query=latest_version.version)](https://galaxy.ansible.com/aramirol/linux)
[![Licence](https://img.shields.io/github/license/aramirol/ansible-collection-linux?logo=license)](https://github.com/aramirol/ansible-collection-linux/blob/main/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/aramirol/ansible-collection-linux?logo=github)](https://github.com/aramirol/ansible-collection-linux/commits/main)

## Tested with Ansible
Tested with the stable releases of Ansible 2.9 and 2.10 and the development version of Ansible


## Dependencies
```yaml
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
```bash
ansible-galaxy collection install aramirol.linux
```


You can also include it in a `requirements.yml` file and install it via `ansible-galaxy collection install -r requirements.yml` using the format:
```yaml
collections:
  - aramirol.linux
```

See [Ansible Using collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html) for more details.

## More information
- [Ansible Collection overview](https://github.com/ansible-collections/overview)
- [Ansible User guide](https://docs.ansible.com/ansible/latest/user_guide/index.html)


## Licensing
GNU General Public License v3.0 or later

See [LICENSE](https://github.com/aramirol/ansible-collection-linux/blob/main/LICENSE) to see the full text.

<!---
## Contributing to this collection
If you want to develop new content for this collection or improve what is already here, please open an issue or create a PR.
-->
