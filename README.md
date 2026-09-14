# Mini Ansible DevOps Project

This project demonstrates basic Ansible automation for a DevOps environment.

## Technologies

- Linux
- Ansible
- YAML
- Jinja2
- Nginx
- Git/GitHub

## Project Structure

```text
ansible-mini/
├── inventory
├── site.yml
├── vars.yml
└── templates/
    └── devops.txt.j2

What This Project Does
Uses an Ansible inventory
Uses a main Ansible playbook
Uses variables from vars.yml
Uses a Jinja2 template
Creates a configuration file
Ensures Nginx is running
Demonstrates Ansible idempotency

Run the Project
ansible-playbook -i inventory site.yml
Verify
cat /tmp/devops.txt

Expected output:

Application: Mini DevOps Application
Status: Running
Message: Ansible deployment is successful!

Ansible Result
ok=4
changed=0
failed=0

This project was created as hands-on DevOps practice.



