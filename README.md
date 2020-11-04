# Django Admin Black

**Modern template for Django admin interface** coded in **Django Framework** by **AppSeed** [Web App Generator](https://appseed.us/app-generator)

<br>

## Why Django Admin Black?
- UI Kit: **[Black Dashboard](https://www.creative-tim.com/product/black-dashboard?AFFILIATE=128200)** (Free version) provided by **Creative-Tim**
- New fresh look
- Responsive mobile interface
- Useful admin home page
- Minimal template overriding
- Support RTL and LTR template
- Easy integration

<br />

## Screenshots

![Django Admin Black - Template project provided by AppSeed.](https://raw.githubusercontent.com/app-generator/django-dashboard-black/master/media/django-dashboard-black-screen.png)

<br>

## Installation

```bash
$ pip install git+https://github.com/app-generator/django-admin-black.git
$ # or
$ easy_install git+https://github.com/app-generator/django-admin-black.git
```

* Add 'admin_black' application to the INSTALLED_APPS setting of your Django project settings.py file (note it should be before 'django.contrib.admin'):

```python
    INSTALLED_APPS = (
        ...
        'admin_black.apps.AdminBlackConfig',
        'django.contrib.admin',
    )
```


* All programs you add in **INSTALLED_APPS** should look like this: **APP_NAME.apps.APP_NAMEConfig**.

> In this feature, we considered that each App can have its own icon, so we ask users to use this feature according to the method. Also in apps.py of each program according to the example add the icon field in the corresponding class. You can go **[here](https://django-dashboard-black.appseed.us/ui-icons.html)** to use more icons
