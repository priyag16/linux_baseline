🛡️ Linux Baseline – Ansible Collection
An opinionated baseline automation for Linux systems focused on initial configuration, hardening, and standardization. This collection helps ensure consistency, security, and audit-readiness across RHEL-based environments.

📌 Role Included
linux_baseline.baseline

✅ Key Features
Installs essential system packages and utilities

Sets up user accounts with SSH key-based access

Applies security settings (sudoers, limits, etc.)

Manages and enables core system services

Supports idempotent and repeatable deployment across environments

🚀 Quick Start
Install the Collection:
bash
Copy
Edit
ansible-galaxy collection install priyag16.linux_baseline
Sample Playbook:

yaml
Copy
Edit
- name: Apply Linux Baseline
  hosts: all
  collections:
    - priyag16.linux_baseline
  roles:
    - baseline
Run with your inventory file to harden and configure systems consistently.

💡 Use Cases
New server provisioning

Ensuring compliance across dev, staging, and prod

Establishing DevSecOps standards

Audit prep and reducing manual effort

🔧 Technologies Used
Ansible
YAML
RHEL-based systems

📄 License
This project is licensed under the MIT License.

🙌 Contributions
Pull requests and feedback are welcome! Feel free to fork and customize for your environment.

👤 Author
Priya Goel
📌 https://github.com/priyag16
💬 Linux Admin | Automation Enthusiast | Azure Fundamentals
