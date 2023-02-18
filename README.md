# Newspaper-Agency
Django project that helps redactors to add/update/delete topics and newspapers in a convenient service
# Base structure of project 
![Base structure](https://github.com/Bohdan2001007/Newspaper-agency/blob/main/drawio.png)
# Installation
- git clone https://github.com/Bohdan2001007/Newspaper-agency
- cd Newspaper-agency
- python3 -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt
- python manage.py migrate
- python manage.py runserver
# Demo
Use the following command to load prepared data from fixture to test and debug your code:

python manage.py loaddata taxi_service_db_data.json

After loading data from fixture you can use following superuser (or create another one by yourself):

Login: admin.user
Password: bestpassword

python manage.py loaddata taxi_service_db_data.json

After loading data from fixture you can use following superuser (or create another one by yourself):
Login: admin.user
Password: bestpassword
![Landing page] (https://github.com/Bohdan2001007/Newspaper-agency/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-18%20%D0%B2%2020.40.52.png)
