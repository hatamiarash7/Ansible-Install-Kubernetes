# Install Kubernetes ( Ansible )

[![Build Status](https://app.travis-ci.com/hatamiarash7/Ansible-Install-Kubernetes.svg?branch=main)](https://app.travis-ci.com/hatamiarash7/Ansible-Install-Kubernetes) [![Molecule](https://github.com/hatamiarash7/Ansible-Install-Kubernetes/actions/workflows/molecule.yml/badge.svg)](https://github.com/hatamiarash7/Ansible-Install-Kubernetes/actions/workflows/molecule.yml)

You can use this role to install [Kubernetes](https://kubernetes.io).

## How-to

First you need instal the role:

-   Clone this role:

    ```bash
    git clone git@github.com:hatamiarash7/Ansible-Install-Kubernetes.git install_kubernetes
    ```

-   Or you can install using galaxy:

    ```bash
    ansible-galaxy install hatamiarash7.install_kubernetes
    ```

Then, Include role in Playbook:

```yml
- hosts: all
    roles:
        - hatamiarash7.install_kubernetes
```

## Dependency

You should install **Docker** first. Use [install_docker](https://github.com/hatamiarash7/Ansible-Install-Docker) role.

---

## Support

[![Donate with Bitcoin](https://en.cryptobadges.io/badge/micro/bc1qmmh6vt366yzjt3grjxjjqynrrxs3frun8gnxrz)](https://en.cryptobadges.io/donate/bc1qmmh6vt366yzjt3grjxjjqynrrxs3frun8gnxrz) [![Donate with Ethereum](https://en.cryptobadges.io/badge/micro/0x0831bD72Ea8904B38Be9D6185Da2f930d6078094)](https://en.cryptobadges.io/donate/0x0831bD72Ea8904B38Be9D6185Da2f930d6078094)

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/D1D1WGU9)

<div><a href="https://payping.ir/@hatamiarash7"><img src="https://cdn.payping.ir/statics/Payping-logo/Trust/blue.svg" height="128" width="128"></a></div>

## Contributing

Don't be shy to be a contributor 😉

1. Fork it !
2. Create your feature branch : `git checkout -b my-new-feature`
3. Commit your changes : `git commit -am 'Add some feature'`
4. Push to the branch : `git push origin my-new-feature`
5. Submit a pull request

## Issues

Each project may have many problems. Contributing to the better development of this project by reporting them.
