> - ping command: 
````
ansible -i hosts all -m ping
````
> - create file command: 
`````
ansible -i hosts all -m copy -a "dest=/home/admin/toto.txt content='Bonjour eazytraining'"
`````
> - setup command :
````
ansible -i hosts all -m setup
````