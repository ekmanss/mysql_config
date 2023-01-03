docker exec -it **** /bin/bash
mysql -u root -p
use mysql
grant all privileges on *.* to 'hfer'@'%';
flush privileges;
