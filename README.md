
#Crude nodes

## Delete Action

```
ansible-playbook tower.yml -e "tower_action=delete" -e "ansible_python_interpreter=/home/skamithi/ansible-env/bin/python"
```

## Create Action

```
ansible-playbook tower.yml -e "tower_action=create" -e "ansible_python_interpreter=/home/skamithi/ansible-env/bin/python"
```

