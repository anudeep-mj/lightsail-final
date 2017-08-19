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