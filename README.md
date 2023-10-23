# Config and stuff for my workstation

## Description

This repository uses ansible to deploy the workstation's configuration :
* it sets the desktop environments (currently [AwesomeWM](https://awesomewm.org/), [i3](https://i3wm.org/) or [qtile](https://qtile.org/))
* it customizes the termninal and bash prompt (with [starship](https://starship.rs/) and [kitty](https://sw.kovidgoyal.net/kitty/))
* it installs [vim](https://vimhelp.org/) with its configuration and plugins
* it installs some other usefull packages

## Usage

Clone the repository, cd into your local copy and then lanch the playbook :
```shell
ansible-playbook -i hosts playbook.yml
```

## Requirements

You will needed sudo rights and ansible :
```shell
user    ALL = NOPASSWD: ALL
```
