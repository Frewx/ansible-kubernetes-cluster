# Bootstrapping a kubernetes cluster using ansible
 
 Creating a kubernetes cluster via ansible.
 
# Prerequisites:
* You should have a user named 'ansible' on all of the hosts.
* You should configure passwordless root for ansible user
* You should configure ssh access with ansible user's ssh key.

After cloning this repo you can bootstrap your cluster with
```
ansible-playbook install-kubernetes.yml -v
```
Currently tested on Ubuntu 18.04
