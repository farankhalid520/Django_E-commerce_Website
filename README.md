# Django_E-commerce_Website
Created an E-commerce website using Django

#Features
User Authentication & Management Using django-allauth
Filtering & Searching Items By Category
Adding & Removing Items From/To The Cart
Add Likes To Product
Cart Management
Adding Coupons While Ordering To Cut Down Price
Commercial & User Friendly Checkout Process Using Dynamic Form
Handling Payment Using Stripe Api Gateway
Order History
Request Refund
Customized Default Django Admin Dashboard

#Directory Layout
Django E-commerce Website App's directory structure looks as follows::

E-commerce-Website-Django/
    |---core
    |--djangoecommerce
    |---static
    |---static_in_env
    |---templates
    |---.env
    |---manage.py
    |---.gitignore
    |---requirements.txt
    |----readme.md

#Run the following commands

$ git clone https://github.com/MoinulHossainNabil/E-commerce-Website-Django.git
$ cd E-commerce-Website-Django

$ pip install virtualenv

$ virtualenv venv_name

$ source venv_name/Scripts/activate  # Using Git Bash

$ pip install -r requirements.txt

$ python manage.py migrate
$ python manage.py createsuperuser --user <username> --email <email>
$ python manage.py runserver

#Static Files

If you don't see the styling work, just run the following command:
$ python manage.py collectstatic

#Models
UserProfile
Item
Category
OrderItem
Cart
Address
Payment
Coupon
Refund

#Stripe
I have used Stripe for handling payment of the order. Stripe officially provides card numbers for the testing purpose of their API's. So use Card Number 4242 4242 4242 4242 and specify a future a date like 12/30 in MM while filling up the payment form for an order to make.
