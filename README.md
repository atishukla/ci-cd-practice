# ci-cd-practice
Repo to have ansible and docker related content for clouds and vms

For now add --extra-vars for sudo password while running ansible

ansible-playbook -i provisioning/hosts.ini provisioning/site.yml --extra-vars "ansible_sudo_pass=xxx"

Step 1:
Create ubuntu user and add it to sudo group
adduser ubuntu
usermod -aG sudo ubuntu
ssh-copy-id ubuntu@<ip>

TODO:
Create password less sudo for ubuntu user
Automate the provisioning process