# Ansible Docker role

This Ansible role will install the Docker engine from the Docker Ubuntu
repository. The role is tested and designed for use on Ubuntu 16.04.

## Installation

```
cd roles

git clone https://github.com/Kumiko/ansible-docker.git docker
```

## Usage

Include the role in your playbook:

```
- hosts: your_docker_hosts
  roles:
    - name: docker
```
