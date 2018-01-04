# Vagrant with Laravel
Vagrant Server with Ubuntu 16.04 and with webframework Laravel

# Requirements
Local installation of vagrant

# How to setup
To use this application you will need to pull the project into your local machine. 
After this you will go to the project root and open a command field.
Use the command "Vagrant up" and wait for the installation to complete. 
The following step will be to access the machine over the command "vagrant ssh". 

After the box is up vagrant ssh to the machine and get assigned ip address via ifconfig.
Now modify your hostsfile and point to laravel.dev. Finally visit https://laravel.dev in your browser.

## MariaDB 10.1

MariaDB is set up to listen public which means we can reach the database directly without additional ssh tunnels.

Credentials:

    username: root
    password: root
    database: development
    
