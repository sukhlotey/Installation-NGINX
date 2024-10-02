# Installation-NGINX
Tutorial for Nginx server for linux
Installation:
### Step 1:
* sudo apt update
### Step 2:
* sudo apt install nginx -y
### Step 3:
Once the installation is complete, start Nginx and enable it to run on boot:
<br>
* sudo systemctl start nginx
* sudo systemctl enable nginx
### Step 4:
Adjust your firewall settings (if necessary)
if you have firewall enabled, then allow HTTP and HTTPS traffic:
<br>
* sudo ufw allow 'Nginx Full'
### Step 5:
Verify Nginx Installation
<br>
* sudo systemctl status nginx
**************************************
Now open on browser to see default welcome page for nginx server by:
<br>
* http://localhost

![Screenshot from 2024-09-28 11-54-01](https://github.com/user-attachments/assets/d5102388-1038-4cad-bbe2-41abbe890898)
