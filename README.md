# Mozio


Functions
---------------

1. Create, Update, Delete, Lists Provider.
2. Create, Update, Delete, Lists ServiceArea.
3. Search Polygon according to lat and long.

Getting Started

	To work on the test code, you'll need to clone project's repository to your local computer. If you haven't, do that first.

	bitbucket repo :

	git clone

	1)Create a Python virtual environment for your Django project. This virtual environment allows you to isolate this project and install any packages you need without affecting the system Python installation. At the terminal, type the following command:

		$ virtualenv -p python3.6 venv

	2)Activate the virtual environment:

		$ source venv/bin/activate

	3)Install Python dependencies for this project:

		$ pip install -r requirements.txt

	4)For Database schema:

		$ python manage.py migrate

	5)Create Super User

		$ python manage.py createsupersuer

	6)Start the Django development server:

		$ python manage.py runserver

	6)Run tests:

		$ python manage.py tests


Rest APIs
---------------
	http://127.0.0.1:8000/document/