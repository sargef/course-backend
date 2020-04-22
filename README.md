# course-backend
 
 ** Get files**
download files
inside root folder run 'npm install'

**Push files to Heroku for app backend api**
sign up for a heroku account

**In termial**
git init
git add .
git commit -m "first commit"
heroku login
heroku create
heroku addons:create jawsdb
git push heroku master


**create a jawsdb database within heroku**

go to app creation on heroku, open 'open app'
You should see this if it worked 'message: "Welcome to the REST API project!"'

open your app and copy the url in the browser
paste the url inside your client folder which is inside your config file in your editor like this and save:



open up the app config details and inside app, select resources
then select Jawsdb mysql




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
npm run build
git init
git add .
git commit -m "first commit"
heroku login
heroku create "SOME_NAME_YOU_WANT_TO_CALL_YOUR_FRONTEND_APP"
git push heroku master


Check out your frontend app and try to sign up and create courses
Remember to att at http address for images from online

Any errors and cd back to your root folder and run 'heroku logs --tail'
to check your terminal output of any errors












