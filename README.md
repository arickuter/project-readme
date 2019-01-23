# Catalog Project - Hosted

## SSH connection 
IP: 35.177.156.240  
Port: 22

### I cannot change to port to 2200. It just doesn't work. I have been locked out 3 times now. I enable it on the firewall, change it in the config file and restart the ssh service but it all doesn't work. Maybe the port is reserved by something else.

## URL to hosted web application
http://35.177.156.240.xip.io

## Internal server error
The latest error is no module named database_setup and I have no idea how to fix it.


## Setup:
Followed the setup course for linux webserver on Udacity [here](https://classroom.udacity.com/courses/ud299)  
- The web applications files are in /var/www/itemcatalog/itemcatalog  
- The WSGI file is in /var/www/itemcatalog and is called 'myapp.wsgi'  
- The virtual machine created is called flask


## Software:  
- python  
- apache  
- flask  
- sqlalchemy  
- oauth2client  
- requests
