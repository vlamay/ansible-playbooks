# Ansible Playbooks

Reusable Ansible playbooks and roles for system hardening, patch management, and security compliance.

## Overview

This repository contains production-ready Ansible playbooks and roles used in enterprise environments for:

- **System Hardening**: CIS Benchmarks compliance automation
- **Patch Management**: Automated security updates and patch deployment
- **Security Compliance**: ISO 27001, PCI DSS compliance automation
- **Configuration Management**: Standardized system configurations

## Structure

```
.
├── playbooks/          # Main playbooks
├── roles/              # Reusable roles
├── inventories/        # Inventory files
├── group_vars/         # Group variables
└── requirements.yml    # Role dependencies
```

## Requirements

- Ansible >= 2.9
- Python >= 3.6

## Usage

```bash
# Install dependencies
ansible-galaxy install -r requirements.yml

# Run playbook
ansible-playbook -i inventories/production playbooks/hardening.yml
```

## Features

- ✅ CIS Benchmarks compliance automation
- ✅ Security hardening for Linux systems
- ✅ Automated patch management
- ✅ Compliance reporting
- ✅ Multi-environment support (dev/staging/prod)

## Contributing

Contributions are welcome! Please read CONTRIBUTING.md for guidelines.

## License

MIT License
