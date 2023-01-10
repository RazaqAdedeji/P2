## Documentation for Project 2

**Command/Installation performed with output**

`sudo apt update`

`sudo apt install nginx`

![install nginx](./images/install%20ngnix.png)

`sudo systemctl status nginx`
![system status nginx](./images/sudo%20systemctl%20status%20nginx.png)

`curl http://localhost:80`
![localhost](./images/curl%20localhost80.png)

`web browser  http://<Public-IP-Address>:80`
![web browser ip](./images/welcome%20to%20ngnix.png)

'sudo apt install mysql-server'
![install mysql-server](./images/install%20mysql-server.png)

'sudo mysql'
![sudo mysql](./imageS/sudo%20mysql.png)

'ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'PassWord.1';'

'sudo mysql_secure_installation'

'sudo mysql -p'
![secure installation](./images/sudo%20mysql%20-p.png)

'sudo apt install php-fpm php-mysql'
![install php-fpm php-mysql](./images/install%20php-fpm%20php-mysql.png)

'sudo mkdir /var/www/projectLEMP'

'sudo chown -R $USER:$USER /var/www/projectLEMP'

'sudo nano /etc/nginx/sites-available/projectLEMP'

![site-available](./images/%3Aetc%3Anginx%3Asites.png)

'sudo ln -s /etc/nginx/sites-available/projectLEMP /etc/nginx/sites-enabled/'

'sudo nginx -t'
![nginx](./images/sudo%20ngnix%20-t.png)

'sudo unlink /etc/nginx/sites-enabled/default'

'sudo systemctl reload nginx'
![reload nginx](./images/sudo%20systemctl%20status%20nginx.png)

'sudo nano /var/www/projectLEMP/info.php'

'http://`server_domain_or_IP`/info.php'
![info.php](./images/php%20version.png)

'sudo rm /var/www/your_domain/info.php'

'mysql> CREATE DATABASE `example_database`;'

'mysql>  CREATE USER 'example_user'@'%' IDENTIFIED WITH mysql_native_password BY 'password';'

'mysql> GRANT ALL ON example_database.* TO 'example_user'@'%';'

'mysql -u example_user -p'

![example_user](./images/mysq%5D%20-u%20example_user.png)

'mysql> SHOW DATABASES;'
![show database](./images/show%20Database.png)

'mysql> INSERT INTO example_database.todo_list (content) VALUES ("My first important item");'

'mysql>  SELECT * FROM example_database.todo_list;'

'nano /var/www/projectLEMP/todo_list.php'

'http://<Public_domain_or_IP>/todo_list.php'
