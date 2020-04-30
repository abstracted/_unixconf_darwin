# OSX Workstation

Simple [Ansible](https://www.ansible.com/) playbook to do the intial setup of my preffered workstation environment.

# What does it do?
- Adds brew
- Adds brew repos
-Adds brew packages
- Adds brew cask packages
- Adds brew cask fonts
- Adds npm packages
- Adds pip packages
- Adds cargo packages
- Configure the systemname hostname ... ect
- Configures osx_defaults such as com.apple.foobar
- Configures system services (brew and launchctl)
- Configures users and optionally adds dotfiles
- Configures docker-machine

## Configuration 
Configurations are stored in `vars/config.yml`.

## Running
To start the playbook, run the following command.

```
./run-playbook
```

If ansible does not exist on your system, it will attempt to install it using `pip`.
