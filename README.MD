# Easy OSX Configurator

Simple [Ansible](https://www.ansible.com/) playbook to configure my preffered osx workstation.

# What does it do?
- Adds brew
- Adds brew repos/taps
- Installs brew packages
- Installs brew cask packages
- Installs brew cask fonts
- Installs npm packages
- Installs pip packages
- Installs cargo packages
- Configure the systemname hostname ... ect
- Configures osx_defaults such as com.apple.foobar
- Configures system services (brew and launchctl)
- Adds users
- Configures dotfiles for users using `stow`
- Configures docker-machine

## Configuration 
Configurations are stored in `vars/config.yml`.

## Running
To start the playbook, run the following command.

```
./run-playbook
```

If ansible does not exist on your system, it will attempt to install it using `pip` via `easy_intall`.
