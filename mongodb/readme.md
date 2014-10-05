# Ansible play book to install mondodb

## Remote host pre-requisites

### make sure you can execute sudo without password prompt:
    sudo vim /etc/sudoers
	
### Add this to the end of the sudoers file
    klo019 	ALL=(ALL) NOPASSWD: ALL
- Where klo019 is you usename


## check your ansible inventory, you can use the included file

## Test ansible with this:
    ansible-playbook deploy_mongo.yml -i inventory.ini --check


