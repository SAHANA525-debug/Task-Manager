## How To Run

1. Install virtualenv: 
pip install virtualenv

2. Open a terminal in the project root directory and run:
virtualenv env

3. Then run the command:
.\env\Scripts\activate

4. Then install the dependencies:
(env) pip install -r requirements.txt

5. Finally start the web server:
(env) python app.py

REQUIREMENTS:
Flask==1.1.2
Flask-SQLAlchemy==2.4.4
gunicorn==19.9.0
itsdangerous==1.1.0
Jinja2==2.11.3
MarkupSafe==1.1.1
SQLAlchemy==1.3.22
Werkzeug==1.0.1

