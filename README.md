# Ansible fail2ban playbook

This is an Ansible playbook for installing fail2ban.

## Requirements

This playbook requires Ansible 1.2 or higher.

## Supported operating systems

This playbook was tested on Ubuntu 12.04 x86_64.

## Variables

Variables which can be configured are located in the `group_vars/all` file.

## Running playbook

```bash
ansible-playbook -i ansible.host setup.yml
```

## License

This playbook is distributed under the
[Apache 2.0 license](http://www.apache.org/licenses/LICENSE-2.0.html).
