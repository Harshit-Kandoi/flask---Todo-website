## Todo Website

# Slightly hints before you run the direct file:-
This Part is Exceuted in terminal
1. Create a Virtual Environment ('python -m venv myenv')
2. Activate your Virtual Environment ('myenv\Scripts\activate\ps1')
3. Install Flask ('pip install flask')
4. Install Flask-SQLAlchemy ('pip install Flask-SQLAlchemy')
5. Ensure the Flask version ('flask --version')
6. According to your Flask version you can import command of Database create form the Documentation of Flask-SQLAlchemy which is available on the google. 
7. Create a database creation query, If database doesn't exist or refuse to working.
from app import app, db
  with app.app_context():
      db.create_all()
       print("Database tables created!")
8. Install Gunicorn ("pip install gunicorn") = You can use this to connect with database if you have the credentials.
9. ("pip freeze requirements.txt") = To get details about the used components.
10. Download jinja2 snippet extension on VScode editor for easy html code creation

# Requirements.txt
1. click==7.1.2
2. Flask==1.1.2
3. Flask-SQLAlchemy==2.4.4
4. gunicorn==20.0.4
5. itsdangerous==1.1.0
6. Jinja2==2.11.3
7. MarkupSafe==1.1.1
8. SQLAlchemy==1.3.23
9. Werkzeug==1.0.1

# Note:-
-This project in developed in the old version of the components. So, it might can cause error in the new version thus, you have to make slightly changes and update its content.
-We tried to use Heroku to deploy our database online but due to its latest version it requires the payment credentials. So, i skipped the connection part you can deploy the database if you are fulfilling the given requirements.

# Project Refrence:-
1. Youtuber - Codewitharry
2. website - bootstrap
3. documention - Flask, Flask-SQLAlchemy
4. Chatgpt.

# This project is still in a develooping phase, for now you can interact with the interface but with time we can deploy more advance features.
