> - ping command: 
````
ansible -i hosts.ini all -m ping
````
> - create file command: 
`````
ansible -i hosts.ini all -m copy -a "dest=/home/admin/toto.txt content='Bonjour eazytraining {{ env }}'"

> - ping command: 
````
ansible -i hosts.yml all -m ping
````
> - create file command: 
`````
ansible -i hosts.yml all -m copy -a "dest=/home/admin/toto.txt content='Bonjour eazytraining {{ env }}'"
