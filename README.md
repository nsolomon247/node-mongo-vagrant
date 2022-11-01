# Welcome to my Mongo DB Vagrant application.

This application utilizes vagrant to create two virtual machines, one a NodeJS API and another MongoDB database.
In order to use this application you need the following:
- An installation of Vagrant
- An installation of either VMWare (M1 Mac) or Virtual Box (All other hardware)
- 30 GB of Hard Drive space for ample machine partitioning (actual application may use less but it's always good to have a buffer)

## Starting the Application
To start the application on Mac (Intel AMD), Linux, or Windows:
- Locate the file in terminal or GitBash.
- Make sure you are in the directory witht the Vagrant File.
- Enter the command ` vagrant up `
- Once the machines are up and running, go to http://nology.training/cicd
- Congratulations you have succesfully used the application!

To start the application on an M series Mac: 
- In the vagrantfile Comment out the code from Line 40 down, uncomment out the code from lines 1 to 40.
- Locate the file in terminal.
- Make sure you are in the directory witht the Vagrant File.
- Enter the command ` vagrant up `
- Once the machines are up and running, go to http://nology.training/cicd
- Congratulations you have succesfully used the application!
# node-mongo-vagrant
