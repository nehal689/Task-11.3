# Task-11.3

 Restarting HTTPD Service is not idempotence in nature and also consume more resources suggest a way to rectify this challenge in Ansible playbook
 
 Task 11.3  Restarting HTTPD Service is not idempotence in nature

hostnamectl set-hostname Controller Node

Step 1 :- Do entry of webserver node in the inventory file and check connectivity
ansible all -m ping
 
Step2 :- Create an ansible-playbook for configure webserver
vi web.yml

Step 3 :- Check the syntax of ansible playbook
ansible-playbook --syntax web.yml

Step 4 :- Run the ansible-playbook
ansible-playbook web.yml

Step 5 :- Check wether the all the system properly of not 
by using the IP address 


 
 
