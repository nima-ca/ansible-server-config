## This repo is for my personal use to config my servers with ansible

feel free to use and contribute to the repo to make it better and add more configs!

## Config

you should change the vars in config-server.yml file for your own use case.
then add a host file with your servers ip addresses and run it with ansible!

to run it with ansible you can use the command below:

```bash

# -k flag is for ssh password and you should use it for the first time!
ansible-playbook -i hosts config-server.yml -u root -k

```

### Important side note!

the config disables password login on the server so make sure you backup your ssh keys!
