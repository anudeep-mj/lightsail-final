## Synopsis

Catalog App hosted on amazon lightsail as WSGI app
App: Catalog App. CRUD Functionality shown.
Uses: Flask, google api, postgresql.



## Pre-requisites
- Access to browser

## Usage:

To play with the app:
Go to: http://34.213.203.248/
The app is hosted here.

To access the lightsail account as grader:
Git clone the project.  
copy the ssh keys in the folder: lightsail-final/keys/ to your ~/.ssh folder
ssh to the machine as follows: ssh -p 2200 -i ~/.ssh/grader grader@34.213.203.248
password: grader


## Authentication and Authorization features
- Firewall added with ssh for 2200 port, opened 80 port for http, 123 for ntp
- Given sudo to grader account
- Key based authentication enabled
- Google Authentication
- Authenticated users can only perform: Add, Edit and Delete category item
- A user can edit and delete only his own items
- packages updatesd as of Aug 19 4 pm

## Software installed
- Postgresql
- SQL Alchemy
- Python
- git
- dependent packages for project to work
- sudo apt-get update and upgrade done to update the entire machine
- apache

## Resources used to complete project:
- https://stackoverflow.com/questions/28213929/psql-fatal-role-does-not-exist
- https://stackoverflow.com/questions/12720967/how-to-change-postgresql-user-password
- https://stackoverflow.com/questions/20242434/how-to-run-python-scripts-on-a-web-servere-g-localhost
- https://askubuntu.com/questions/629995/apache-not-able-to-restart
- https://manpages.debian.org/jessie/apache2/a2ensite.8.en.html
- https://stackoverflow.com/questions/21084791/flask-hello-world-using-apache-and-mod-wsgi-shows-files-in-webroot-only
- https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
- https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-16-04
- https://stackoverflow.com/questions/11919391/postgresql-error-fatal-role-username-does-not-exist
- http://docs.sqlalchemy.org/en/latest/core/engines.html#postgresql
- https://discussions.udacity.com/t/using-postgresql-in-the-linux-final-project/271824
- https://discussions.udacity.com/t/facebook-google-login-trouble/203645
- https://askubuntu.com/questions/174981/how-do-i-configure-ufw-to-allow-ssh-on-another-port
- https://stackoverflow.com/questions/27771273/ssh-connection-using-another-port-in-os-x
- many, many more.. (I have closed many tabs..)