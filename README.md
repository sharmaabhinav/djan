djan
====

Learning django and python


Setup of django in ubuntu
-------------------------

1 ) Install virtualenv ( sudo apt-get install python-virtualenv )

2 ) Create a virtual environment ( virtualenv < name > )

3 ) Activate virtual environment ( source < name >/bin/activate )

4 ) Install django ( easy_install django )


Creating new Django project
---------------------------

1 ) django-admin.py startproject < project name >



Creating an app inside project
------------------------------

1 ) cd < project name >

2 ) python manage.py startapp  < app  name >


Starting django server
----------------------

1 ) python manage.py runserver


Other Useful commands
---------------------

1 ) python manage.py sql < app name > ( prints the sql for models )

2 ) python manage.py validate ( validate models for errors )

3 ) python manage.py syncdb ( create tables for models in database ) 


