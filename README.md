# ItemCatalogWebServer

This README file explains how to connect to the Item Catalog web server that I have created using Amazon Lightsail.

Public IP address of the server: 18.237.6.115

## To ssh into the server:

1. Go to command line interface.
2. Obtain public key.
3. Enter the following on the command prompt: ssh -i grader_key.pem grader@18.237.6.115 -p 2200
4. Grader user password is: grader

## Application URL

http://18.237.6.115 

## Summary of Software that is Installed on Server

Server includes software and packages such as the following to run app:

Flask, SQLite, SQL Alchemy, mod_wsgi, 

The server includes software such as Apache, Python, and SQLite. Apache allows the server to function as a web server so as to allow the application to function. Python allows the code to be deployed on the server. The SQLite software within the server allows for the use of the database.

## References
https://help.ubuntu.com/community/UFW
https://modwsgi.readthedocs.io/en/develop/user-guides/virtual-environments.html
https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-uwsgi-and-nginx-on-ubuntu-16-04
