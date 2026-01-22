# Ansible Playbooks

Collection of Ansible playbooks for automation tasks.

## Playbooks

- **Create_dir.yml** - Create directories on remote servers
- **Delete_dir.yml** - Delete directories on remote servers
- **deploy_nginx.yml** - Deploy Nginx web server
- **first_playbook.yml** - Basic playbook example
- **upgrade_cisco_ios.yml** - Upgrade Cisco IOS firmware
- **requirements.yml** - Ansible Galaxy requirements

## Usage
```bash
ansible-playbook -i inventory.ini <playbook_name>.yml
```

## Requirements

See `requirements.yml` for Ansible Galaxy collections needed.
