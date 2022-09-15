# AWS LAMP STACK IMPLEMENTATION
 ## **This project shows how to implement LAMP**(Linux-Apache-Mysql-Php) on AWS

 ## ..................Installing Apache.........................

 update a list of packages in package manager

 `sudo apt update`

run apache2 package installation

 `sudo apt install apache`

Verify apache2 is running

`sudo systemctl status apache2`

![Image of Apache2 service running](./Images/apache_status.JPG)

verify apache webpage is accessible from the server

`curl http://localhost:80
or
 curl http://127.0.0.1:80`

 To get the ipv4 address of the server run the below command

 `curl -s http://169.254.169.254/latest/meta-data/public-ipv4`

 ![curl output ](./Images/curl_localhostPort80.JPG)

 Lets Confirm the webserver is reachable from the outside network by running the below url on a web browser.

 `http://<Public-IP-Address>:80`

 ![browser output](./Images/testprojectlamp_page.JPG)

 ## ......... Installing MSQL ......................













