## Built using:
- Python with Django framework and Jinja templating language
- Vanilla Javascript

## Getting started:
- Install all the dependencies of this project by typing `pip install -r requirements.txt`
- Migrate the database by typing `python manage.py migrate` on the command line
- Run the project locally by typing `python manage.py runserver` on the command line
    - NB: to run it on your local network, type `python manage.py runserver 0.0.0.0:8000`
- You project will be accessible in your localhost or local network.

## Deployment
For deployment, open `form/settings.py` file and uncomment code from line 131 to 159.
