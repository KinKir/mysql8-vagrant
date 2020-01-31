# MySQL 8 + ubuntu/bionic64
This is a vagrant box with MySQL 8 for development purposes.  

# Installation
git clone 
vagrant up

# Connection
vagrant ssh 

# Credentials
host: 10.20.30.40
user: root
password: root
port: 3306

# Notes
- The provision script will set ```default-authentication-plugin=mysql_native_password```
- Current version of Sequel Pro does not support MySQL 8, you will run into issues when trying to connect. Use MySQL Workbench or TablePlus