# learn-django
Django project step by step.

### Create an environment

```
python3 -m venv environment-name
. bin/ativate
````
The environment after the command above...

```
projectvenv
  |--bin
  |--include
  |--lib
  |--pip.selfcheck.json
  |--pyvenv.cfg
```


#### Note: Command "deactivate" to leave the virtual environment.

```
django-admin.py startproject pilot
```

Your directory structure should look like this

```
projectvenv
  ├──bin
  ├──include
  ├──lib
  ├──pilot (src)
  |   ├──db.sqlite3
  |   ├──manage.py
  |   ├──pilot*
  |   └──templates
  ├──pip.selfcheck.json
  ├──pip.selfcheck.json
  └──pyvenv.cfg
```

Inside the pilot* folder:

```
pilot (src)
├───manage.py
└───pilot
        settings.py
        urls.py
        wsgi.py
        __init__.py
```


#### Note: "." to install the environment locally (current folder).
#### Note: pip freeze *See all installed libraries.

### Clone the blank project as a reference project (Optional)
git clone -b pilot [https://github.com/ericxlive/learn-django.git](https://github.com/ericxlive/learn-django.git)
