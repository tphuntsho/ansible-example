# ansible-example

yum install ansible

git clone https://github.com/kapilsthakkar25/ansible-example
cd  ansible-example

ansible-playbook -l webapp -i inventories/hosts.ini ping.yml

ansible-playbook -l devopslab -i inventories/hosts.ini ping.yml
