# dev-setup-with-ansible

## Command to run the Playbook
```bash
sudo apt update && sudo apt install -y ansible git
git clone https://github.com/sonamdhingrax/dev-setup-with-ansible.git && cd dev-setup-with-ansible
ansible-playbook -i inventory playbook.yml -K
```