# README

## target

install nessary tools, service and other stuff on a ubuntu server

## preconditions

a ubuntu server with ssh accessable, your local machine with ansible present

## configuration

edit `hosts` to change target server, username and pass

## this folder and files are init with command

```shell
ansible-galaxy init build_ubuntu
```

## run playbook with

``` shell
ansible-playbook -i ./hosts server.yml
```
