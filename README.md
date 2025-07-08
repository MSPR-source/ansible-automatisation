# ansible-automatisation
# Ansible Automatisation - POC

Ce projet contient des playbooks Ansible et scripts pour :

- Gérer des incidents sur Windows Server
- Automatiser des tâches avec Ansible et PowerShell
- Intégrer GLPI et Active Directory

## Structure

- `inventory.ini` : liste des hôtes
- `playbooks/` : playbooks Ansible
- `scripts/` : scripts PowerShell/Bash
- `roles/` : rôles Ansible
- `vars/` : variables personnalisées

## Lancement

```bash
ansible-playbook playbooks/incident.yml