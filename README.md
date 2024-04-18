 ![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/2cb4355f-c347-49ae-b100-5045f414efe8)


# Farmer Management System

## Connecting Farmers. Nourishing Communities. 

# Problem statement:

## Consumers: 

Difficulty accessing fresh, locally-grown produce at competitive prices. Limited transparency about farming practices and the origin of food.


## Farmers: 

Difficulty reaching new customers beyond local markets. Reliance on middlemen who take a significant cut of profits. Lack of control over product pricing and distribution.


# Our Solution :

This farmer management system is a two-way platform that facilitates direct interaction and product purchase between consumers and farmers. It aims to minimize the market gap, ensuring fairer prices for farmers and fresher, locally sourced products for consumers.

# Features

## User Management:

1.) User registration and login for both consumers and farmers.
2.) Secure user authentication.
3.) Role-based access control to restrict functionalities based on user type (consumer/farmer).
 
## Farmer Management:

1.) Farmer registration with detailed profile creation (name, timestamp, contact information, etc.).

2.) Ability for administrators to add, edit, and manage farmer profiles.


# Installation:

 ## Clone the repository:

```
https://github.com/Blacksujit/Farmer_management_system.git
```

```
pip install flask
```

```
pip install flask-sqlalchemy
```

```
pip install  mysql-client
```

```
pip install flask-login
```

# for dependencies Requirement's:

```
pip install -r requirements.txt
```


# Database connection:

## Downlode xamp server:

https://sourceforge.net/projects/xampp/

click on next next and install :   (installation window will look like this  ) 

![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/cd3fb803-a75e-4779-a6c5-119227f4326f)


## open xampp server on yur pc :

## open:

![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/fd24d546-ba66-4585-843d-9ae05ae6a537)


## start the xamp server :(navigate to control panel) 

![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/4b0bcc68-73fa-491f-a741-82efc7770d67)


## start the server by clicking on start (as shown  ):

![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/c7c62cb9-764f-4bea-85a4-93bd1bae2e67)

## go to the admin panel of mysql (as shown in image a new window will open)

![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/b827e4b7-8c49-43bd-9bce-74f2e9e2f4ed)


## php admin panel:
![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/ac2d3e86-bd9b-4130-87ce-4c27b683f805)

## click on new (add or creat a database instance):

![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/d071284e-b070-4ea2-94ab-28ea90b44586)


## enter the database name ( specifically " farmers  " ) shown in input box 


![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/1af0d244-3ecb-44f2-9146-1fc3866ea8c7)


## import the database from the project: (As shown )

![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/deb78bea-4c1c-490b-953a-5470c64cedf6)


## click on import or go according to yur admin panel (after choosing dtabase file from project ):


![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/2b43cc82-b482-41d5-b64e-96f60c975cbd)

<br>

![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/b07f6eb7-fed8-4a84-86c5-c3592fc408e0)


## the database will become visible in the sidebar of your admin panel:

![image](https://github.com/Blacksujit/Farmer_management_system/assets/148805811/47066018-5d02-499b-8cee-f45f7697785a)


## Now Navigate to project in your vs code:

## in terminal hit the command


```
python wsgi.py
```

or run the code inside the file wsgi.py


## the developement server will run on port:(according the server provided on yur vs code)

``
 Running on http://127.0.0.1:3000
``

