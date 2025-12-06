# 🧪 Ansible Lab — Baseline + Centralized Logging

This repository contains a real-world Ansible lab environment used to practice DevOps automation:

- 🔹 Baseline OS configuration
- 🔹 Package installation
- 🔹 Login MOTD banner
- 🔹 Centralized logging with rsyslog (server + clients)
- 🔹 Clean role-based architecture
- 🔹 Git + GitHub version control
- 🔹 VS Code Remote SSH development

## 🚀 Quick Start

Run everything:

```bash
ansible-playbook -i hosts.ini playbooks/site.yml
