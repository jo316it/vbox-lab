# VBOX-LAB - My first automation with Vagrant using Virtual Box

# What's it for?
To have a little lab using the Ansible server and two clients.

# How're Works
After building the infrastructure, you'll have control of the Ansible Server across for the SSH connection. To for that, you can use the command below:
```
ssh -p 2222 -i $HOME/vagrant/lab_ansible/.vagrant/machines/ansible/virtualbox/private_key vagrant@127.0.0.1
```
