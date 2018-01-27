# LinuxServerConfiguration
This project is a part of FSND (Full Stack Web Developer) at Udacity.
This project is done to demonstrate installation and configuration of a Linux server to to host a web application. 

# Configuration details
  IP :  13.127.9.96
  
  URL : http://ec2-13-127-9-96.ap-south-1.compute.amazonaws.com/
  
  # Softwares installed
    Upgraded all packages to latest
  
  **Installed below softwares..**
  
    1. Apache2    
    2. mod_wsgi    
    3. Flask
    4. Postgresql
    5. python-pip
    6. python-psycopg2
    7. oauth2client
    
  # Configurations
  
    1. created new user grader
    2. provided sudo access to grader
    3. disabled root and password auth, and default ssh login port 22
    4. enabled ssh login to grader
    5. disabled firewall for all incoming except ports 2200, 123, 80
    6. Created itemcatalog database with user catalog
    7. Deployed itemcatalog application  
    
    
# How to login to linux server as grader
  Use the attached grader private key to login to 13.127.9.96 as grader@13.127.9.96 on port 2200
  
  
    
  

