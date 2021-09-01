[![GitHub stars](https://img.shields.io/badge/dws-ops--002--ansible-ff69b4?&style=plastic)](https://github.com/mi-alkhamis/docker-ansible) [![GitHub license](https://img.shields.io/github/license/mi-alkhamis/docker-ansible?color=green&style=plastic)](https://github.com/mi-alkhamis/docker-ansible/blob/main/LICENSE)  [![GitHub issues](https://img.shields.io/github/issues/mi-alkhamis/docker-ansible?color=red&style=plastic)](https://github.com/mi-alkhamis/docker-ansible/issues)  [![GitHub forks](https://img.shields.io/github/forks/mi-alkhamis/docker-ansible?style=plastic)](https://github.com/mi-alkhamis/docker-ansible/network) [![GitHub stars](https://img.shields.io/github/stars/mi-alkhamis/docker-ansible?color=yellow&style=plastic)](https://github.com/mi-alkhamis/docker-ansible/stargazers)



# Docker ansible

Install docker on Debian-based and RHEL-based distributions.

## Requirements

| Name    | Version |
| ------- | ------- |
| Python  | 2.6     |
| Ansible | 2.10    |

**if you don't have it, simply replace yum by dnf in redhat.yaml file.** 

## Platforms

| Name   | Version       |
| ------ | ------------- |
| Ubuntu | focal, bionic |
| CentOS | 7.4+, 8       |
| RedHat | 7.4+, 8       |

Other OS distributions were not tested but will probably work. 

## Usage

Write a playbook like this

````yaml
- hosts: servers
  roles:
   - docker-ansible
````

then run 

```bash
ansible-playbook -i hosts.ini playbook.yaml -n
```

Wait for a couple of minutes, docker installed :smile:

## Contribute

All contributions are welcome:

- Read the issues, fork the project and do a Pull Request.
- Request a new topic creating a New issue with the enhancement tag.
- Find any kind of errors in the cheat sheet and create a New issue with the details or fork the project and do a Pull Request.

## License

This project is licensed under the GPL-3.0 License  - see the [LICENSE](https://github.com/mi-alkhamis/docker-ansible/blob/main/LICENSE) file for details.

[@dwsclass](https://github.com/dwsclass) dws-ops-002-ansible

