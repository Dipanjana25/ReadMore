# ReadMore
This is a virtual tutor system backend made on Django.

To run on your local machine :

mkdir rdmr
python3 -m venv venv
source venv/bin/activate
git clone https://github.com/Dipanjana25/ReadMore.git
cd rdmr
python manage.py migrate
cp .env.example .env and fill the secret key and debug values in .env
python manage.py runserver
It's running now on https://localhost:8000/
