
#  Django Commands
   Virtual Enviornment
### Type the following command on CMD For starting a new Project 

```
   pip install virtualenvwrapper-win
  
   mkvirtualenv toursite(name of project, anyone)

   pip install django

   django-admin --version (for checking version)

   mkdir toursit (any name u can give to your folder)

   cd tousite (foldername)

   django-admin startproject toursite(name of proj)

  cd toursite(project name)

  python manage.py runserver  
  python manage.py startapp (nameOfApp)
```
  
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

3. Install dependencies:

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
       
## Git Commands

* repo -> repository
* `clone` -> bring a repo down from the internet (remote repository like Github) to your local machine
* `add` -> track your files and changes with Git
* `commit` -> save your changes into Git
* `push` -> push your changes to your remote repo on Github (or another website)
* `pull` -> pull changes down from the remote repo to your local machine

### Learning **git and github**

* `git status` shows all of the files that are **modified, deleted or created** but not saved in commit  yet.
* `git add` tell which file to track. 
   * most of the time we use `git add .` to track. 
   * It's mean to track all of these files that are listed/show after running command `git status`.
   * or we can use `git add index.html` for individual fil/dir.
  
* Now we can do commit with `git commit -m "updated readme.md"` **-m is for msg** 
* or even for more description we can add `git commit -m "updated readme.md" - m "Added git & github commands here"`. This will save code locally, commit is not live on GitHub.
* `git push` command used to push to GitHub.

### SSH Keys

* In order to push to GitHub, we need to improve that u are owner of computer, 
  * First need to generate an ssh key `ssh-keygen -t rsa -b 4096 -C "example@gmail.com"`.

* For more info please check this [SSH Keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#adding-your-ssh-key-to-the-ssh-agent)


* `git push main origin master` origin master is the location where we want to push.

* Let suppose we make a dir locally and want to push/publish on github, then easy way to do is create an empty repo on github and copy url of repo.

* Then `git remote add orgin (link of repo)`.

* `git remote -v` this will tell any remote repo which connected.Then say `git push origin master`. There is shortcut instead of writing origin master say `git push -u origin master` so next time we just can tell `git push`. 

### Git Branching

By default, we have only master branch. We can create other branches to create new feature and that branch will totally separate from master branch. 

`git branch` command will show total branches.

`git checkout` used for switching branches.

`git checkout -b filter-feature` it will create new branch.

`git diff master` this command show what changes have been made between two commands.

`git push` after running this command we will have code like this `git push --set-upstream origin filter-feature` or short version for this is `git push -u origin filter-feature.

**pull changes from GitHub** `git pull` or in PyCharm just click on update. 


`git branch -d branch_name` this command will delete branch.


