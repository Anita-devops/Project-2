## Detailed documentation of Project2

### INSTALLING THE NGINX WEB SERVER

`sudo apt update`
![Apache-file](./Images/Apache-file1.PNG)
![Apache-file](./Images/Apache-file2.PNG)

`sudo apt install nginx`
![Apache-file](./Images/Apache-file3.PNG)
![Apache-file](./Images/Apache-file4.PNG)

*To verify that nginx was successfully installed and is running as a service in Ubuntu*

`sudo systemctl status nginx`
![Apache-file](./Images/Apache-file5.PNG)

*To access the server locally in our Ubuntu shell*

 `curl http://localhost:80`
 ![Apache-file](./Images/Apache-file6.PNG)

 `curl http://127.0.0.1:80`
 ![Apache-file](./Images/Apache-file7.PNG)

*To test how our Nginx server can respond to requests from the Internet*

[Nginx Server response to request](http://100.26.212.185:80)
![Apache-file](./Images/Apache-file8.PNG)

*To retrieve your Public IP address on terminal*

`curl -s http://169.254.169.254/latest/meta-data/public-ipv4`

![Apache-file](./Images/Apache-file9.PNG)


### INSTALLING MYSQL