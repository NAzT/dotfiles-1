# My dotfiles

    sudo apt update
    sudo apt install software-properties-common
    sudo apt-add-repository --yes --update ppa:ansible/ansible
    sudo apt install -y ansible

    git clone https://github.com/NAzT/dotfiles-1.git .dotfiles

    . ~/.dotfiles/bin/dot-bootstrap
    sudo chsh -s /bin/bash nat_w

Configure linux workstation using Ansible.

### Version

ubuntu 18.04
