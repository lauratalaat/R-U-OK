# R U OK
* Uses smartcar API to detect when a car gets into an accident
* Sends driver text message to check if they are okay
* Uses Weather API to warn driver of upcoming weather conditions

## Development Setup
1. Make sure you have python version 3.x: `python --version`
1. Create a python virtual environment (optional):
  `pip install virtualenv`
  `virtualenv env`
  `source env/bin/activate`
1. Install dependencies: `pip install -r requirements.txt`
1. Run `cp config.base.py config.py`
1. Paste your smartcar info into `config.py`
1. Put `http://localhost:8000/exchange` as the redirect URI on the smartcar console
1. Download MongoDB if you don't have it yet
1. Run `chmod 755 run_db.sh`
1. Run `./run_db.sh`
1. Run the server in a different window: `python app.py`
1. Go to `localhost:8000` and register for an account

