# ansible-nginix-install
Installing Nginx using ansible


To create inventory file (hosts):
  sudo nano /etc/ansible/hosts
  
Test to see if you can reach inventory:
  sudo ansible all -m ping --ask-pass

To create playbook (nginx-playbook.yml):
  sudo nano nginx-playbook.yml
  
Run playbook:
  1. sudo ansible-playbook nginx-playbook.yml --ask-pass
  2. sudo ansible-playbook nginx-playbook.yml --ask-become-pass
