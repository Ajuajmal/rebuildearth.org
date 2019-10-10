# rebuildearth.org
rebuildearth.org website
# Rebuild Earth Disaster Management , Awarness and Alertness Platform

# Quick Run !

### Run the website in a local env

- create a virtual env and activate

  `virtualenv -p python3 env`

  `. env/bin/activate`
- install requirements

  `pip install -r requirements.txt`
- Creat a .env file and copy contents of .env.sample

  `touch .env`

  `cp .env.sample .env`
- make migrations

  `python3 manage.py makemigrations`

  `python3 manage.py migrate`

- run the server

  `python3 manage.py runserver`
