# Basic Wordpress playbook based on LEMP stack

## Prerequisites
1. In order to run the playbook, place the IP address of your desired server in the [hosts](https://github.com/pitdeer/wordpress-nginx-playbook/blob/master/hosts) file.
2. Put the hostname of the server in the [webservers](https://github.com/pitdeer/wordpress-nginx-playbook/blob/master/group_vars/webservers) file.
3. Put a secure password for Wordpress in the [webservers](https://github.com/pitdeer/wordpress-nginx-playbook/blob/master/group_vars/webservers) file. 
4. The server that will run Wordpress requires:
 - public key of the ansible machine
 - installed python 2.7

## Running
In order to run the playbook, go to its directory and run the folowing command:
```
ansible-playbook -i hosts playbook.yml
```
