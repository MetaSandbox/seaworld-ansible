# seaworld-ansible
Ansible playbooks for automated rancher environment configuration
## requirements
ansible >=2.2.0.0
ssh root access to managed servers
## use
Run the playbook in terminal in test mode
`> ansible-playbook aquarium-dev.yml --check`
Run the playbook in terminal in flight mode
`> ansible-playbook aquarium-dev.yml`
