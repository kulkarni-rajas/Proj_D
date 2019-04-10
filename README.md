A very trivial Django App with home page and admin area.
To Build this App

mkdir project

cd project

git clone https://github.com/kulkarni-rajas/Proj_D.git

pipenv --three

pipenv shell

pip install -r requirements.txt

cd april

python manage.py migrate

python manage.py runserver

use at http://127.0.0.1.8000/
