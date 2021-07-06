# Django Student Management System π¨βπ

A modern Student Management System π¨βπ with features like Interactive Dashboard π© Attendance Management π«Provide Feedback β Result Generation π Leave Application π

## Development 
Note : Make sure you have Python version 3.7+

Environment Setup π

`$ git clone `

`$ cd Django_Student_Management_System/`

If virtualenv is not installed 

`$ pip install virtualenv`

Create a virtual environment

`$ virtualenv venv`

Activate the environment everytime you open the project

`$ source venv/Scripts/activate`

Install requirements π 

`$ pip install -r requirements.txt`

Run migrations for Database 

`$ python manage.py makemigrations`

`$ python manage.py migrate`

Create superuser for Admin Login π

`$ python manage.py createsuperuser`

Enter your desired username, email and password. Make sure you remember them as you'll need them in future.

eg.

    Username: admin
    
    Email: admin@admin.com
    
    Password: HighlyConfidentialPassword

All Set! π©

Now you can run the server to see your application up & running π

`$ python manage.py runserver`

To exit the environment β

`$ deactivate`

Every time you want to open the application in browser, make sure you run:

`$ source venv/Scripts/activate`

`$ python manage.py runserver`


### License β

```
MIT License

```  
