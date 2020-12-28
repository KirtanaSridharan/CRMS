# CRIME RECORDS MANAGEMENT SYSTEM

## INTRODUCTION

A crime record management system software is a web based application that provides facility for reporting online crimes. 
This project focuses a little on a few  such as maintaining details of all the officers of all stations in the city, name of the stations, and maintain complaints filed by the users. The users can file complaints online and view the status of their complaints at their homes without having to come down to the stations.

### ABOUT THIS PROJECT:-

This system provides 3 user panels-admin, police officer and the public user. During the login process, the system checks  for the authentication of the user in each panel. For instance, the police officer and the public user cannot login from Admin interface and same goes for the other two interfaces.


The Admin module is provided with the following functionalities:
1. View/Manage all officers
2. View/Manage police stations
3. View/Manage crime categories
4. View all FIRs

The Police Officer module is provided with the following functionalities:
1. View officers in my station
2. View crime categories
3. View FIRs
4. Approve/Reject FIRs

The Public User module is provided with the following functionalities:
1. View all police stations
2. Register a complaint
3. View my complaints

The Technologies used for this project are:
* Django Python framework
* MySQL
* Apache Web server
* HTML
* CSS
* JavaScript

Prerequisites -
* Windows OS
* Web browser - Chrome, Microsoft Edge, etc..


### For executing the project-

Steps to be followed:
1. Install django - You can go to the following link for installation https://docs.djangoproject.com/en/3.1/intro/install/
2. Install MAMP local server environment - You can go to the following link for installation https://documentation.mamp.info/en/MAMP-Windows/Installation/
3. Download the zip file provided and travel to the folder crms in command prompt where the entire code of the project is present.
4. Create a django environment. 
5. Go to MAMP, start the server and go to website. Click on phpmyadmin.
6. Create a database with the name crimedb.
7. In your command prompt, type in commands to first create a superuser, makemigrations to add the tables to the database, migrate to the same and run the server.
8. Your website is up and running.

Please follow the documentation of Django provided to get the project running. https://docs.djangoproject.com/en/3.1/


