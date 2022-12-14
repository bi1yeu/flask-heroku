# Skeleton Flask Heroku app

via https://geekyhumans.com/how-to-deploy-flask-api-on-heroku/#Deploying-a-Flask-App-on-Heroku

## Create app

Create virtualenv and install Python requirements

```sh
pyenv virtualenv 3.10.9 <app-name>
pyenv activate <app-name>
pip install -r requirements.txt
```

Create app in Heroku

```sh
heroku login
heroku create <app-name>
```

## Run locally

```sh
flask run --reload --port 8080
```

## Deploy

```sh
heroku login
git push heroku main
```
