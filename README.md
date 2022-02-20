
#  Django Commands
   Virtual Enviornment
### Type the following command on CMD For starting a new Project 

 ` pip install virtualenvwrapper-win `
 
` mkvirtualenv toursite(name of project, anyone) `

` pip install django `

` django-admin --version (for checking version) `

` mkdir toursit (any name u can give to your folder) `

` cd tousite (foldername) `

` django-admin startproject toursite(name of proj) `

` cd toursite(project name) `

` python manage.py runserver `

` python manage.py startapp (nameOfApp) `

### How to run a Clone (from GitHub) Django Project?

First, clone project then need to need to install all requirements of project by running following command.

### In Git/Cmd

1. Install virtualenv with pip:

    ```pip install virtualenv```
2. Create new virtual env with python3:

    ```virtualenv venv -p full_path_to_python``` # e.g. use `where python` to find the path to correct python    
3. Activate virtual env:

    ```venv\Scripts\activate```

4. Install dependencies:

   ```pip install -r requirements.txt```

After that you have to configure the database. You have to make migrations and then migrate.

   `python manage.py makemigrations`

to create migration files for the models already defined in the codes you have cloned.

  `python manage.py migrate`
  
## Clone in PyCharm IDE, Follow this procedure
       
First, clone project then need to install all requirements of project by running following command.

`pip install -r requirements.txt`

After that you have to configure the database.You have to make migrations and then migrate.

       python manage.py makemigrations

to create migration files for the models already defined in the codes you have cloned.

        python manage.py migrate


