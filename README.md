# SAP BASIS Automation using Ansible

## Project Overview

This repository contains Ansible automation projects developed for common SAP BASIS administrative tasks.

The goal of this project is to reduce manual effort by automating SAP administration activities such as health checks, profile backups, kernel pre-checks, SAP start/stop operations, and SAP HANA monitoring.

---

## Technologies Used

- Ansible
- YAML
- Jinja2
- Linux
- SAP BASIS
- SAP HANA
- Git
- GitHub

---

## Folder Structure

```
inventory/
playbooks/
roles/
templates/
files/
reports/
screenshots/
ansible.cfg
README.md
```

---

## Projects Included

### 1. SAP Daily Health Check

Features:

- Hostname
- Operating System
- Kernel Version
- CPU Information
- Memory Usage
- Disk Usage
- SAP Process Status
- Health Report Generation

---

### 2. System Health Report

Features:

- Hostname
- Disk Usage
- Memory Usage
- Uptime
- Report Generation using Jinja2

---

### 3. SAP Profile Backup Automation

Features:

- Create Backup Directory
- Timestamp-Based Backup
- Copy SAP Profile
- Automatic Versioning

---

### 4. SAP Kernel Upgrade Pre-Check

Features:

- Filesystem Validation
- Memory Check
- SAP Process Check
- Kernel Information
- Dynamic Report Generation

---

### 5. SAP Start/Stop Automation

Features:

- SAP Start Simulation
- SAP Stop Simulation
- Error Handling
- Block / Rescue / Always
- Execution Report

---

### 6. SAP HANA Health Check

Features:

- HANA Service Check
- Database Status
- Memory Monitoring
- Disk Usage
- Dynamic Report Generation

---

## Skills Demonstrated

- Ansible Playbooks
- Roles
- Jinja2 Templates
- Variables
- Facts
- Loops
- Register
- Conditions
- File Module
- Copy Module
- Template Module
- Error Handling
- SAP BASIS Automation

---

## How to Run

Example:

```bash
ansible-playbook playbooks/system_health.yml
```

or

```bash
ansible-playbook playbooks/kernel_precheck.yml
```

---

## Future Improvements

- Email Notifications
- HTML Reports
- Multi-Server Inventory
- SAP Transport Validation
- HANA Backup Monitoring
- Automatic Log Cleanup

---

## Author
**Parul Rajoriya**
SAP BASIS Administrator
