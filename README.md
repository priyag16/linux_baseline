Documentation for the collection.
# linux_baseline
# Ansible Collection: linux_baseline

This Ansible collection provides an opinionated baseline automation for Linux servers — focusing on initial configuration, hardening, and standard setup across environments. 

It includes a reusable role that ensures consistency, security, and audit-readiness for enterprise systems.

---

## 📁 Role: `linux_baseline.baseline`

### Features
- Adds essential system packages and utilities
- Sets up user accounts with SSH keys
- Applies security configurations (limits, sudoers, etc.)
- Enables and configures system services
- Supports idempotent execution across RHEL-based systems

---

## 📦 Installation

You can install the collection using:

```bash
ansible-galaxy collection install priyag16.linux_baseline
