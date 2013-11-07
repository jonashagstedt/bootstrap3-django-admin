bootstrap3-django-admin
=======================

Bootstrap3 for Django admin

## Description

There are a few packages out there to apply Bootstrap styling and markup for Django admin, but so far none of them were using Bootstrap 3.


## Installation 

1.  pip install -e git://github.com/jonashagstedt/bootstrap3-django-admin.git#egg=admin_bootstrap

2. Make sure you put ```'admin_bootstrap3',``` before django.contrib.admin in installed apps


    INSTALLED_APPS = (
    	...
        'admin_bootstrap3',
        'django.contrib.admin',
     )


3. That's it!


## Additional notes
Bootstrap is great, however Font Awesome (fontawesome.io) is nicer.

If you want to use Bootstraps default icons, just udpate the remplates and replace all "fa" classes with "glyphicons"

## Credits

*  bootstrap-datepicker by Stefan Petre, with improvements by Andrew Rowls
(http://www.eyecon.ro/bootstrap-datepicker)

* bootstrap-timepicker by Joris de Wit (http://jdewit.github.com/bootstrap-timepicker)

* Chosen select box enhancement by Patrick Filler (https://github.com/harvesthq/chosen)
