# My dotfiles

    git clone https://github.com/NAzT/dotfiles-1.git .dotfiles

    . ~/.dotfiles/bin/dot-bootstrap
    
    sudo apt update
    sudo apt install software-properties-common
    sudo apt-add-repository --yes --update ppa:ansible/ansible
    sudo apt install ansible
    
Configure linux workstation using Ansible.

### Languages

Languages are managed with [asdf](https://asdf-vm.com/#/).

- Ruby
- Golang
- Nodejs
- Python
- Elixir
- Terraform

### System

- fzf
- git
- tmux
- vim
- zsh

### Services

- redis

### Packages

- snap
- apt

## Bootstrap

Firt setup installation run the dot-bootstrap command.

```
$ ./bin/dot-bootstrap
```

After that you can run any scripts defined in the `$DOTFILES_PATH/bin`

```
$ dot-bootstrap
```
