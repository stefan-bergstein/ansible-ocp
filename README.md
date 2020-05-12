# ansible-ocp
Few tests with Ansible and OCP



## Create OCP Project for a user 

- Create project
- Make user project admin using RoleBinding

Create:
```
ansible-playbook create-project.yml --extra-vars PROJECT=test2-project --extra-vars REQUESTER=developer --extra-vars
```


Delete:
```
ansible-playbook create-project.yml --extra-vars PROJECT=test2-project --extra-vars REQUESTER=developer --extra-vars state=absent
```
