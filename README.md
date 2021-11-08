# Ansible Role: ansible-base_apps_freeipa_client

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_freeipa_client-purple?style=flat)](https://galaxy.ansible.com/     lotusnoir/apps_freeipa_client)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_freeipa_client.svg)](https://github.com/lotusnoir/ ansible-apps_freeipa_client/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_freeipa_client?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/52290)](https://galaxy.ansible.com/lotusnoir/apps_freeipa_client)
![Ansible Quality Score](https://img.shields.io/ansible/quality/52290)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/        licenses/Apache-2.0)




## Role variables

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `company_domain` | "" | ldap domain |
| `freeipa_server_fqdn` | "" | freeipa main server |
| `freeipa_server_admin_password` | "" | freeipa server admin password |

## Examples

	---
	- hosts: base_apps_freeipa_client
	  become: yes
	  become_method: sudo
	  gather_facts: yes
	  roles:
	    - role: ansible-base_apps_freeipa_client
	  vars:
        company_domain: example.com
        freeipa_server_fqdn: "ipa.example.com"
        freeipa_server_admin_password: "strongpassword"
	  environment: 
	    http_proxy: "{{ http_proxy }}"
	    https_proxy: "{{ https_proxy }}"
	    no_proxy: "{{ no_proxy }}

## License

This project is licensed under MIT License. See [LICENSE](/LICENSE) for more details.
