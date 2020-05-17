
Create a virtual env with python 3
> python3 -m venv venv

Activate the virtual env 
> source venv/bin/activate

Install flask & dependencies
> pip install flask

> pip install flask-wtf

Set the FLASK_APP environment variable.
> export FLASK_APP=microblog.py

Run the app
> flask run

Open your browser on localhost:5000