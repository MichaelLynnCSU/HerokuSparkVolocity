# spark-heroku-example

## Frontend Deployment

https://coursework.vschool.io/deploying-with-surge/

## Backend Deployment

https://github.com/MichaelLynnCSU/spark-heroku-example

Change maven-heroku-plugin version from 0.4.4 to 1.1.3

spark-heroku-example ..... change it to app name in POM.

## Heroku Add Git

heroku login

heroku git:remote -a spark-heroku-mike

## Heroku Update Project

Move to root project directory

heroku login

git add .

git commit -m "Initial commit"

git push heroku master

heroku open

https://spark-heroku-mike.herokuapp.com/hello
