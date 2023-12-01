# Ansible configuration scripts

Ubuntu ansible installation:

    sudo apt-add-repository ppa:ansible/ansible

    sudo apt update

    sudo apt install ansible

To setup local environment:

    ansible-pull -U git@github.com:ikerUrle/ansible.git --ask-become-pass
