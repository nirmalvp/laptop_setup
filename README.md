Ansible playbook to set up a Ubuntu laptop from scratch.

## Usage

```bash
ansible-playbook playbook.yml --ask-become-pass

# Work machine
ansible-playbook playbook.yml --ask-become-pass --tags work

# Personal machine
ansible-playbook playbook.yml --ask-become-pass --tags personal
```

## Requirements
- Ubuntu (tested on Ubuntu 24.04)
- Ansible (`pip install ansible` or `apt install ansible`)
