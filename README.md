# Shopmart
Groomed my skills on E-commerce Web Application with payment gateway for future aspects.

# Goal
The goal is to build an E-commerce web application which enables the user login/register and also buy/view products. Also provide Admin side which can be used to add/edit/delete products, its price/quantity/description and also show dashboard for user profile/address/cart.


# System Design

![Capture](https://user-images.githubusercontent.com/62649065/109478257-052a9e80-7a9f-11eb-8558-e1ab0ebe9616.PNG)


# Steps to run application:
1. First of all install all the packages which are included in requirements.txt
2. Run python manage.py makemigrations which generates the SQL commands
3. Run python manage.py migrate which executes those SQL commands in the database file
3. Run python manage.py createsuperuser to which creates admin as a super user.
4. After successfully creating admin username and password run python manage.py runserver to run an emulated server on your local computer
5. Now login in to admin (i.e. http://127.0.0.1:8000/admin) where you would see all the tables generated due to migration command
6. Now This is the most important you must need to update product table with your own images/prices/product-name etc. without this you would not see any product which popped up in the application, also this images will directly be saved in media folder which will be created automatically in the root folder
7. Try to Signup/login as a user and you will see each and every products and their details uploaded by admin
8. and that's it...Happy Hacking

# Screenshots

![i6](https://user-images.githubusercontent.com/62649065/109491670-e2ed4c80-7aaf-11eb-9d8d-c16479af1917.jpg)

![i5](https://user-images.githubusercontent.com/62649065/109491681-e84a9700-7aaf-11eb-946c-481fb9e26d79.jpg)

![i4](https://user-images.githubusercontent.com/62649065/109491689-ec76b480-7aaf-11eb-9155-d3ae18fb840b.jpg)

![i3](https://user-images.githubusercontent.com/62649065/109491706-f1d3ff00-7aaf-11eb-884b-dbcb14a6cff1.jpg)

![i2](https://user-images.githubusercontent.com/62649065/109491800-0dd7a080-7ab0-11eb-9751-4834d95dc480.jpg)

![i1](https://user-images.githubusercontent.com/62649065/109491819-1334eb00-7ab0-11eb-9f5d-9c64ed857b3e.jpg)



# Author
Pratik Ahir





















