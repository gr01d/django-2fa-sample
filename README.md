## [django-2fa-sample](https://github.com/gr01d/django-2fa-sample)
An attempt to harden django application using 2fa.

### Requirements:
```
Django==2.2.17
django-two-factor-auth
django-two-factor-auth[phonenumberslite]
```

### Commands for development (Not for Deployment)
```
$ sudo apt install python3-venv

$ python3 -m venv myvenv

$ source myvenv/bin/activate

$ python3 -m pip install -r requirements.txt

$ python3 manage.py migrate

$ python3 manage.py createsuperuser

$ python3 ./manage.py addstatictoken <username>

$ python3 manage.py runserver
```

## How


## TO DO

## Changelog

## License

GNU AGPL v3

## Credits/References/Tutorials

[django-two-factor-auth](https://github.com/Bouke/django-two-factor-auth)

[django-otp](https://github.com/django-otp/django-otp)
