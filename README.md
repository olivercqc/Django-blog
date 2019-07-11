# Django-blog

This blog is developed by *Python3.7* and *Django2.2*

Since I'm a **poor guy** and got no money to rent a web server, You need to set up ur personal python enviroment to see this *simple and crude* blog

### I strongly recommend u try *virtualenv*
- first: just type `pip install virtualenv virtualenvwrapper` in ur command line and press `Enter`, just a little reminder, if u are working on `Windows` system, u need to type `pip install virtualenv virtualenvwrapper-win`
- second: type `mkvirtualenv environment-name` to create a virtual environment, here we assume the *environment-name* is *djangoweb*, and ur command line will looks like `(djangoweb)>:` after the setup process
- third: just `clone` *this repo* and `cd` into *it*, then just type `pip install -r requirements.txt` to install all the required library to run this blog
- finally: type `python manage.py runserver` to see this blog
