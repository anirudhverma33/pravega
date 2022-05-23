# branch for the 2022 pravega website made in flask

The app is called pravega
There are two blueprints (admin and events)
Application factory is to be used even though this is a small app

## Running the application

Install python>=3.7

### Make a virtual environment in python first

To do this, for open `Windows terminal` or `cmd` or `teminal`,
navigate to this git repository,
make sure that you are on the website2022 branch and type
```
python -m venv venv
```
To go to this virtual environment, type
```
. venv/bin/activate
```
Then install flask by running:
```
pip install flask`
```

Finally to run the app,
on Windows(cmd), type

```
set FLASK_APP=pravega
set FLASK_ENV=development
flask run
```
an bash or other linux/unix terminal
```
export FLASK_APP=pravega
export FLASK_ENV=development
flask run
```
on powershell,
```
$env:FLASK_APP = "pravega"
$env:FLASK_ENV = "development"
flask run
```
