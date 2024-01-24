Set up a virtual environment to contain all the packages needed
```
pip install --upgrade distro-info
pip3 install --upgrade pip==23.2.1
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate
```
Set up the Python runtime and test the template project.
```
pip install -U -r requirements.txt
```

Create the initial migrations and generate the database schema:
```
python3 manage.py makemigrations
python3 manage.py migrate
```

Run server.
```
python3 manage.py runserver
```

Project Starting Point Screenshot

![image](https://github.com/cagri32/Django-Cloud-App-with-Database/assets/43071105/5f268772-2d20-4233-a221-991ee37aff72)

Admin Site View

![image](https://github.com/cagri32/Django-Cloud-App-with-Database/assets/43071105/c625283c-4ed8-4694-b7e5-4fb9eea4db27)

Exam Page for a course

![image](https://github.com/cagri32/Django-Cloud-App-with-Database/assets/43071105/e943ab2f-fec2-45be-a44e-c7cdd4abb65f)

Exam results after submitting an exam

![07-final](https://github.com/cagri32/Django-Cloud-App-with-Database/assets/43071105/a73944aa-45d1-4b30-9142-5b9b43662917)

**ER Diagram**

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)
