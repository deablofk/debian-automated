# Debian-Automated
NOTE: this is my personal debian-system, so it fits my needs and it is designed to be run only on a new debian installation

## Description
Automatic install debian with pre-configured settings and post-install with ansible

## Installation
```bash
git clone https://github.com/deablofk/debian-automated
cd debian-automated
ansible-playbook ansible/workstation-debian.yaml --ask-become-pass # you can change the yaml by another present in ansible folder
```

