# wordpress-site-aws

Project-WordPress Site on AWS
Objective-


-First of all I created  VPC with a public and private subnet with CDIR range of 10.0.0.0/16 called wordpress.



-I proceeded to create a public subnet and a private subnet in different in two AZs.




-I then created an internet gateway named IGW-Wordpress.



-I proceeded to create an EC2 instance named WordPress-instance



-I then went on to purchase a domain name from Google Domain named DigitalBoost.com.



-Proceeded to DNS settings and added two custom A records of the domain name.



-I ssh to connect the instance.



-I continued by running the command “sudo apt update”



-I also ran the command “sudo apt upgrade”



-Went ahead to run “sudo apt install nginx mariadb-server php-fpm php-mysql”




-To install word press, I CD to /var/www directory.



-Furthermore ls into the /var/www to get the html folder




-To get wordpress I used the command “sudo wget https://wordpress.org/latest.tar.gz


-To extend it to wordpress I used the command “sudo tar –xzvf latest.tar.gz”



-I did change of ownership using command “sudo chown –R www-data:www-data wordpress




-Also I used the command “sudo find wordpress/ -type d –exec chmod 755




-I proceeded to use the command “sudo mysql –u root –p




-I applied privileges with the command “flush privileges”




-Furthermore to look at our web server, I cd into /etc/nginx/




-I proceeded to cd sites-available/




-Then I ran “sudo vim wordpress.conf




-I added the code for the webserver in the editor



-I proceeded to configure the database with password and email.




-Connected the database to the webserver



-I ran “sudo snap install core; sudo snap refresh core



-Ran “sudo snap install –classic certbot



-I used certbot to get the ssh certificate.



-This project is very challenging in the aspect of paying for different services.



-But I was able to find a way around it.


-I have learnt a lot from this project.

