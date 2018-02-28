# gitlab-provisioning

Prova installazione gitlab con strumenti devops: virtualbox, vagrant, ansible

Uso del [playbook per ansible](https://github.com/geerlingguy/ansible-role-gitlab)

Secondo l'esempio di [ansible-vagrant-example](https://github.com/geerlingguy/ansible-vagrant-examples)

## Requisiti:
* VirtualBox
* Vagrant

```
$ cd /home/example/gitlab-provisioning
$ vi Vagrantfile
$ vagrant up
$ vagrant status
$ vagrant provision
```
in caso di errori, rieseguire:
```
$ vagrant reload && vagrant provision
```

accedere all'indirizzo: https://192.168.77.101 oppure a localhost:10443
