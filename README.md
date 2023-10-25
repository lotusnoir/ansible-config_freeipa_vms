# ansible-config_freeipa_vms

[![Galaxy Role](https://img.shields.io/badge/galaxy-config_freeipa_vms-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/config_freeipa_vms)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-config_freeipa_vms.svg)](https://github.com/lotusnoir/ansible-config_freeipa_vms/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-config_freeipa_vms?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/config_freeipa_vms)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/config_freeipa_vms)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/config_freeipa_vms)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Description](#description)
- [Requirements](#requirements)
- [Role variables](#role-variables)
- [Examples](#examples)
- [License](#license)
- [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Complete the vm enrollment after freeipa client installation, add the vms in hostgroups and create hba rules to access it
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: config_freeipa_vms
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-config_freeipa_vms


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
