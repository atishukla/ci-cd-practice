# ci-cd-practice
Repo to have ansible and docker related content for clouds and vms

For now add --extra-vars for sudo password while running ansible

ansible-playbook -i provisioning/hosts.ini provisioning/site.yml --extra-vars "ansible_sudo_pass=xxx"

TODO:
Create password less sudo for ubuntu user
Automate the provisioning process