# CTF

This web app is a beginners CyberSecurity CTF webpage that teaches basic web security principles, such as directory brute force attacks. The website opens up to a basic webpage with a login screen that the user should attempt to bypass and attempt to gain admin privileges. A register screen allows the user to register. To start this, clone the repository and enter the command `python manage.py runserver` to start the server and enter the provided URL to connect (http://127.0.0.1:8000/). 

I wrote this software to learn the basics of Django and build my first CTF website so that I can use this framework for future projects as well as understand Django better which will help me in my future career.

[Software Demo Video](https://youtu.be/g-TF045FR8s)

# Web Pages

The base webpage (/) allows the user to either login or register which will redirect them to the respective webpages:
![image](https://user-images.githubusercontent.com/66894542/201243179-edd97112-ddea-46f5-801d-ddb3af70b083.png)

If they are already logged in, they will be greeted and allowed to logout. Here is an example of the admin being logged in:
![image](https://user-images.githubusercontent.com/66894542/201243317-d71c60f4-7892-4d00-8fc7-20422917da5a.png)

The login page (/login) allows the user to login or can redirect them to the register page if they have not already registered:
![image](https://user-images.githubusercontent.com/66894542/201243607-44f8cd2c-f418-4ef6-bddb-1e275d2fa0d5.png)

The register page (/register) allows the user to create an account and automatically logs them in if they successfully create an account:
![image](https://user-images.githubusercontent.com/66894542/201243707-269bf985-3edb-4579-8657-22c40f43f1d5.png)

Finally, the builtin admin page allows the admin to add/delete users and add/remove users to groups:
![image](https://user-images.githubusercontent.com/66894542/201243853-c33c3508-e853-42d1-8b0d-52073f96526b.png)

# Development Environment

I used the following Django commands to create my base project:
```
django-admin startproject my_project_name
python manage.py startapp my_app_name
python manage.py runserver
```
I used Visual Studio Code as my IDE and also used crispy forms for my CSS with the command: `pip install django-crispy-forms`. Finally, I used Python in the Django project I made with the commands above to create dynamic webpages. I also used the Django authenticate and forms functionality to create my login and register pages. 

# Useful Websites

* [Django Documentation and Tutorial](https://docs.djangoproject.com/en/3.0/contents/)
* [Use Django built in login functionality](https://learndjango.com/tutorials/django-login-and-logout-tutorial)

# Future Work

* Add more CTF functionality
* Create a forgot password page
* Add MFA
