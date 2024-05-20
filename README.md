### Welcome

You need to create a virtualenv and install the requirements.txt content into it.

You can check the following [drf](https://django-rest-framework.org) site!

``` bash
virtualenv dj-rest-api
source dj-rest-api/bin/activate.fish
pip install -r requirements.txt
```

Now we can create our project.

``` bash
django-admin startproject APITest
cd APITest
django-admin startapp quickstart
cd ..
python3 manage.py migrate
```




