# Two Factor Authentication for Django Admin Panel

In this project, I've used Google Authenticator for implementing Time-based One-time Password (TOTP) to validate user while login to the Django admin panel.

## Steps to run the project
1. Install dependancies by `pip install -r requirements.txt`
2. Database migration by `python manage.py migrate`
3. Create superuser by `python manage.py createsuperuser`
4. Finally run the project by `python manage.py runserver`

For detailed guide visit my [blog](https://medium.com/aubergine-solutions/quick-start-two-factor-authentication-in-django-admin-panel-d15ceeb62591).

## Working demo
![Working Sample](https://github.com/jp9573/django-admin-2fa/blob/master/working_demo.gif)
