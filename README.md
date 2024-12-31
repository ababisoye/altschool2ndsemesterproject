# altschool2ndsemesterproject
Creating a prototype for a web application
## Project Description
This project deminstrastes the setup of a webserver and deployment of a simple HTML page using EC2 on aws

#Public IP Details
Public IP Address: http://54.167.2.117
DNS Address: http://ababisoye.ddns.net

#Step by step of how it works
first of all, i created an ec2 instance on aws with ubuntu as the operating system then generated an ssh key on my phyical device.
Ran chmod 400 command to make sure only the owners have permision to read and every other person deosnt have access to the private keys
Using gitbash i went into the directory where the private key was downloaded and connected to ec2 instance using te public dns
next up we installed apache server ,configure the server to allow all http traffic and ran the server then deployed the "index.html" file

#Configuring HTTP for the web server using a free SSL Certificate
used noip.com to generate a dns name for my public ip :http://54.167.2.117
DNS Name: ababisoye.ddns.net
Installed certbot using command: "sudo apt install cerbot python3-certbot-apache -y"
Requested an SSL Certificate using command: sudo certbot --apache

#SCREENSHOT
![altschool project screenshot](https://github.com/user-attachments/assets/cc7bf954-746e-44c7-804e-7e7aafea5b4b)


#AUTHOR
Abisoye Shoyemi

