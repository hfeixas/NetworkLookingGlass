# NetworkLookingGlass

Network looking glass is an open source project aimed at faciliating a GUI capable integration with Napalm, and network devices.
There are 5 active integrations so far but the code has been written in a way where adding features will be as simple as editing a single file. 
There are a lot of features in this application. Including unversal search and smart filtering of both devices and commands.
Please see below some of the working features.

## Installation:

to run simply clone this repo and follow these steps:

```python
pip3 install -r requirements.txt
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py createsuperuser
python3 manage.py runserver
Navigate to 127.0.0.1:8000/admin to add your devices.
```

## Features:

### Arp Table Lookup
 ![alt text](https://github.com/hfeixas/NetworkDashboard/blob/master/Images/ArpTables.gif)
 
### Command Executor
![alt text](https://github.com/hfeixas/NetworkDashboard/blob/master/Images/Command.gif)

### BGP Status
![alt text](https://github.com/hfeixas/NetworkDashboard/blob/master/Images/BGP.gif)

### Interfaces
![alt text](https://github.com/hfeixas/NetworkDashboard/blob/master/Images/Interfaces.gif)


