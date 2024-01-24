# Add_a_Captcha_to_Django_admin
Add a Captcha to Django admin

reference link
---------------
https://youtu.be/JYEwOSBcKvY?si=tdJ9zQoBuUzAiC3z


Step: 1
https://django-simple-captcha.readthedocs.io/en/latest/usage.html#installation

Step: 2
https://github.com/a-roomana/django-multi-captcha-admin

pip install django-multi-captcha-admin

Step: 3
-------
INSTALLED_APPS = [
	...
	'multi_captcha_admin',
	'django.contrib.admin',
	...
]

Step: 4
--------
pip install django-simple-captcha
pip install django-recaptcha2


Step:5
-------

MULTI_CAPTCHA_ADMIN = {
    'engine': 'recaptcha2',
}