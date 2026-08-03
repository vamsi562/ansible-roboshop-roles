# ansible-roboshop-roles

## Commands
-----------

```
ansible-playbook -i inventory.ini -e "component=mongodb" main.yaml
ansible-playbook -i inventory.ini -e "component=mysql" main.yaml
ansible-playbook -i inventory.ini -e "component=redis" main.yaml
ansible-playbook -i inventory.ini -e "component=rabbitmq" main.yaml
ansible-playbook -i inventory.ini -e "component=catalogue" main.yaml
ansible-playbook -i inventory.ini -e "component=cart" main.yaml
ansible-playbook -i inventory.ini -e "component=payment" main.yaml
ansible-playbook -i inventory.ini -e "component=user" main.yaml
ansible-playbook -i inventory.ini -e "component=shipping" main.yaml
ansible-playbook -i inventory.ini -e "component=frontend" main.yaml
```