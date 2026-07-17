# Ansible Windows Automation

A collection of Ansible playbooks for automating common Windows Server administration tasks using WinRM.

## Features

- Collect Windows system information
- Create directories
- Copy files to Windows servers
- Create local users
- Install Windows features
- Manage Windows services
- Restart Windows services
- Delete files
- Reboot Windows servers
- Run Windows Update

## Project Structure

```
ansible-windows-automation/
├── inventory/
├── group_vars/
├── host_vars/
├── playbooks/
└── roles/
```

## Technologies

- Ansible
- WinRM
- Windows Server
- YAML
- Jinja2

## Usage

```bash
ansible-playbook -i inventory/hosts.ini playbooks/collect_windows_info.yml
```

## Author

Sarvotham Golla
