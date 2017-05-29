**Exampe ansible hosts file:** 

**FILE**: __/etc/ansible/hosts__

```
[control]
control ansible_host=10.0.1.23

[web]
node-1 ansible_host=10.0.1.21
node-2 ansible_host=10.0.1.24
node-3  ansible_host=10.0.1.28

[haproxy]
haproxy ansible_host=10.0.1.222

[all:vars]
ansible_user=vagrant
ansible_ssh_private_key_file=~/.ssh/id_rsa
```
