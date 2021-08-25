git clone chat_django

...

python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt

cd chat_django

./manage.py makemigrations chat 
or
./manage.py makemigrations

./manage.py migrate

./manage.py runserver

