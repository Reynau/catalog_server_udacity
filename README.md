# Linux Server Configuration


IP Address: 3.122.253.77  
Port: 2200

URL: http://3.122.253.77/

Software installed: 
- Python
- Pip
- Virtualenv
- Mod_wsgi
- Python packages:
  - flask
  - flask_wtf
  - sqlalchemy
  - firebase_admin
  
 Configurations made:
 - Updated and upgraded packages
 - Created ```grader``` user with sudo access
 - Generated key pairs for ```grader``` user and forced key based authentication
 - Configured and enabled UFW to allow ports for WWW, NTP, SSH (non-default port)
 - Configured Apache with mod_WSGI to run the python application with Apache
 - Configured the python virtual environment

Third-party resources used:
- http://flask.pocoo.org/docs/1.0/deploying/mod_wsgi/
- Stack-Overflow to solve minor issues
- Udacity Troubleshoot repo provided by mentors: https://github.com/jungleBadger/-nanodegree-linux-server-troubleshoot
