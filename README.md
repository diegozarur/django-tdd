**Test Driven Development of a Django RESTful API**


>  - Install the requirements
>  - Create a Sqlite database
>  - Apply the migrations
>  - Run the server


First access virtual venv
> source env/bin/activate


Install requirements
> pip install -r requirements.txt

In Database
> python manage.py makemigrations
> python manage.py migrate

And them to execute tests
> python manage.py test
