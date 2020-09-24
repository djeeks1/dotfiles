# Config and stuff for my workstation

## Description

This repository uses ansible to deploy the workstation configuration. Here is what it installs and configure :
* some usefull packages 
* vim whith its configuration and plugins
* customize bash and its prompt

## Usage

Clone the repository, cd into your local copy and then lanch the playbook :
```shell
ansible-playbook -i hosts playbook.yml
```

## Requirements

You will needed sudo rights and all ansible requirements :

```shell
user    ALL = NOPASSWD: ALL
```
