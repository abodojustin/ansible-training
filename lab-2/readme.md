````
ansible -i hosts all -m ping
````
`````
ansible -i hosts all -m copy -a "dest=/home/admin/toto.txt content='Bonjour eazytraining'"
`````
````
ansible -i hosts all -m setup
````