The Web/Frontend is the service in RoboShop to serve the web content over Nginx. This will have the web page for the web application. 
Developer has chosen Nginx as a web server and thus we will install Nginx Web Server.

Install Nginx
yum install nginx -y

Start & Enable Nginx service
systemctl enable nginx  
systemctl start nginx

Try to access the service once over the browser and ensure you get some default content.
http://<public-IP>:80

Remove the default content that web server is serving.
