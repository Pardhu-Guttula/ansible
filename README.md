# Ansible Repository

This repository contains Ansible playbooks and roles for infrastructure automation.

## Quick Start

1. Clone: `git clone https://github.com/your-username/ansible-repo.git && cd ansible-repo`
2. Install Ansible: `sudo apt-get update && sudo apt-get install ansible`
3. Run a playbook: `ansible-playbook -i inventory playbook.yml`

## Useful Commands

- **Install Roles:** `ansible-galaxy install username.role_name`
- **List Hosts:** `ansible-inventory --list -i inventory`
- **Ping Hosts:** `ansible all -i inventory -m ping`
- **Run Ad-Hoc Command:** `ansible all -i inventory -a "your_command"`

## Directory Structure
![tree](https://github.com/Pardhu-Guttula/ansible/blob/main/image.png)