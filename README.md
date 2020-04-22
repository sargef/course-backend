# course-backend
 
 ** Get files**
download files
inside root folder run 'npm install'

**Push files to Heroku for app backend api**
sign up for a heroku account
.env file

git add .
git commit -m "first commit"
heroku login
heroku create
git push heroku master


**create a jawsdb database within heroku**
heroku addons:create jawsdb
go to app creation on heroku
open up the app and inside app, select resources
then select Jawsdb mysql

**inside terminal**
heroku git:clone -a YOUR-APP-NAME
cd YOUR-APP-NAME

copy details from jawsdb configuration and past into a .env file like this


**heroku config for backend**
install sql platform for database configuration: heidisql https://www.heidisql.com/download.php
create the following inside heidisql

create a new database
add your credentials from jawsdb to connect to your app
click on open
save 
right click on database, select create new, then table

**create 3 tables like the following**
Users (capital U)
then click on add (to select new columns)

Courses (capital C)
sqlite_sequence

**cd into client folder**
npm install
git add .
git commit -m "first commit"
heroku login
heroku create "SOME_NAME_YOU_WANT_TO_CALL_YOUR_FRONTEND_APP"
git push heroku master

Check out your frontend app and try to sign up and create courses
Remember to att at http address for images from online












