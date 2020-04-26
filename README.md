# Django-REST-API-User-Authentication

The REST API will handle Token based User Registration and Authentication and can be used
for any desktop or mobile clients

## 🚀 Getting Started - Local

### macOS Mojave 10.0+, Catalina 10.1+

```bash
# clone the repo
git clone https://github.com/Abhishek5101/Django-REST-API-User-Authentication
# change into project directory
cd Django-REST-API-User-Authentication/
# start virtual enviornment
source bin/activate
# install dependencies
pip3 install requirements.txt
cd api/
python manage.py runserver

Visit http://127.0.0.1:8000/auth/users/ to create new user
Visit http://127.0.0.1:8000/auth/token/login to log in
```

## :hammer: Built With

-   [Django](https://www.djangoproject.com/) - Web Framework
-   [Django REST API](https://www.django-rest-framework.org/) - Django REST API
-   [Djoser](https://pypi.org/project/djoser/) - djoser library provides a set of Django Rest Framework views
-   [SQLite3](https://sqlite.org/index.html) - Database


## 📝 License

By contributing, you agree that your contributions will be licensed under its Apache License.



## User Registration
![](user_registration.gif)

## User Authentication 
![](user_login.gif)

## Testing invalid data input
![](checking_data.gif)
