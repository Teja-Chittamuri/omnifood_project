Host our website using cloud computing concept
==========================================================

Pre-Requsistes
-----------------
1. AWS EC2 Instace
2. Apache2 webserver Installed on Ec2 Instance

Steps:
--------
1. Create  an ec2 istance in AWS.
2. Install apache2 webserver in our ec2 instance using the below cmds

    sudo apt update
 
    sudo apt install apache2 -y 

3. Check the status of the apache2 webserver using the cmd 
    systemctl status apache2 
3. Clone the src code from the Github to EC2 instance using cmd 
    git clone url 
4. Copy the src to apache2 webserver home dierctory (/var/www/html).
5. Add a HTTP Security Group Rule to allow traffic on Port 80.
6. Access our application using Public IP Address. ( https://54.219.38.60:80 )
