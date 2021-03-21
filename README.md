Write an Ansible PlayBook that does the following operations in the managed nodes:

Configure Docker
Start and enable Docker services
Pull the httpd server image from the Docker Hub
Run the docker container and expose it to the public
Copy the html code in /var/www/html directory and start the web server

Solution
To do this task I created these ansible playbook :
1. Docker_httpd: configure yum to install docker ,download and start services, also launch the contine from httpd images and expost the port also 
 
