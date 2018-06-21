# Linux-Server-Configuration
Linux Server Configuration for Udacity Nanodegree

# Accessing Server

URL: http://ec2-18-216-211-187.us-east-2.compute.amazonaws.com

IP: 18.216.211.187

SSH Port: 2200

# Configuration Changes

1. Updated and Upgraded ubuntu 
2. Checked to see if system in UTC (it already was)
3. Changed default port to 2200. Updated in lightsail networking tab aswell.
4. Activiated uncomplicated firewall with default deny incoming and default allow outgoing. Allowed, 2200 for ssh, 80 for html, and 123 for ntp
5. Created grader user, and gave sudo access to grader
6. Created ssh key pair on local machine for grader, and added to authorized_keys file.
7. Turn off password based authentication.
8. Installed apache2 and mod_wsgi
9. Installed Git
10. Cloned catalog repo to /var/www/catalog
11. Created catalog.wsgi file
12. Installed and started virtual environment (virtualenv).
13. Installed project dependencies (pip, Flask, request, oauth2client, sqlalchemy, psycopg2)
14. Configured virtual host
15. Installed and configured Postgresql
16. Lanuch app

# Helpful Resources

https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-16-04
