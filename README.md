
##  Django and DRFCommands
   Virtual Enviornment

### Followings commands (Cmd/Git) are used for starting a proj

```
   pip install virtualenvwrapper-win
  
   mkvirtualenv Travel(name of project, anyone)

   pip install django

   django-admin --version (for checking version)

   mkdir toursite (any name u can give to your folder)

   cd tousite (foldername)

   django-admin startproject toursite (name of proj)

  cd toursite(project name)

  python manage.py runserver  
  python manage.py startapp home (nameOfApp)
```

### Django Rest Framework

`pip install djangorestframework`

Then also need to add in settings.py

`INSTALLED_APPS = [
    ...
    'rest_framework',
]`

For wiring nestable `pip install drf_writable_nested` is used for writing
nested obj, in other words *serializers with Foreign Key*.

**For more detail [click me](https://github.com/beda-software/drf-writable-nested)**
  
### How to run a Clone (from GitHub) Django Project?  Window setup

First, clone project then need to need to install all requirements of project by running following command.

### In Git/Cmd

1. Install virtualenv with pip:

       pip install virtualenv
 
2. Activate virtualenv in cmd/:

       venv\Scripts\activate

3. Activate virtualenv in GitBash:

        cd venv (virtual env)
        source ./Scripts/activate
        
4. Deactivate in Gitbash

         deactivate 

6. Install dependencies:

       pip install -r requirements.txt

After that you have to configure the database. You have to make migrations and then migrate.

       python manage.py makemigrations

to create migration files for the models already defined in the codes you have cloned.

       python manage.py migrate
  
## Clone in PyCharm IDE, Follow this procedure
       
First, clone project then need to install all requirements of project by running following command.

       pip install -r requirements.txt

After that you have to configure the database.You have to make migrations and then migrate.

       python manage.py makemigrations

to create migration files for the models already defined in the codes you have cloned.

       python manage.py migrate
       

### [CLI & GIT Commands](https://github.com/MTayyab10/Cli-Git)

