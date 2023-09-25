[![ansible](https://img.shields.io/badge/Ansible-red?style=for-the-badge&logo=ansible)](https://www.ansible.com/)

[![HitCount](https://hits.dwyl.com/data-tangles/ansible.svg?style=for-the-badge&show=unique)](http://hits.dwyl.com/data-tangles/hyperv-homelab)

# Hyper-V Homelab

This repo contains Ansible playbooks specific to building Hyper-V VM's and associated infrastructure for my Production and Lab Hyper-V environment.

## Getting started

You would need to start by [installing](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) Ansible onto a machine where you would like to run playbooks from.

In my case, I have Ansible installed on a dedicated node which also acts as an Azure DevOps agent so that I can run all my playbooks via CI/CD pipelines.

The [documentation](https://docs.ansible.com/) site has everything you need to setup all components for Ansible so I encourage you to read through it and familiarize yourself with the key concepts.
