# django

## django installation on Linux.
step 1: install virtualenv

~~~bash
sudo apt-get install python3-virtualenv
~~~

step 2: install virtualenvwrapper

~~~bash
sudo pip3 install virtualenvwrapper
~~~

![image](https://github.com/peternjathi/django/assets/108217436/062c4917-1923-43bf-b447-121c11da3f11)

Step 3: Add the virtualenvwrapper shell configuration

~~~bash
sudo nano ~/.bashrc
~~~

Add the following line at the end of the file: 

~~~bash
source /usr/local/bin/virtualenvwrapper.sh
~~~

Save the file and restart your terminal to apply the changes.
-run.
~~~bash
 mkvirtualenv "your desired name"
~~~
step 4: Install django on your newly installed environment.
~~~bash
pip install django
~~~
To start a new django project run:
~~~bash
django-admin startproject "directory_name"
~~~
step 5: To open your virtual environment run.
~~~bash
workon "virtualenv_name"
~~~
