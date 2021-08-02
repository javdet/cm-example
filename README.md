# cm-example

## Requirements
* ansible >= 2.9

## Run playbook
```
ansible-playbook -i inventory/development/hosts -v playbook.yml
ansible-playbook -i inventory/production/hosts -v playbook.yml
```