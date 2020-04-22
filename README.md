Course - restAPI - Backend (Nodejs) Frontend (React)
 


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
Remember to only add web addresses for images hosted online such as 'https://image.png'

Any errors just cd back to your root folder and run 'heroku logs --tail'
to check your terminal output of any errors. It is usually pretty helpfull to help fix any bugs or gives you an idea on what to google for a solution.











<h1><b><p align="center">React App Api Image Search</p></b></h1>


<h3><b><p align="center">Click to see live Course App!!</p></b></h3>
<a href="https://course-restapi-38.herokuapp.com/" target="_blank"><img src="https://github.com/sargef/course-restapi-backend-nodejs-frontend-react-live/blob/master/assets/course.png"></a>

<h2><b><p align="center">React App</p></b></h2>

<h1><p align="center"> :sparkles: This react app will require the following config to be hosted online :sparkles: </p></h1>
<br />


<p align="center"><a><img src="https://github.com/sargef/react-app-api-image-search/blob/master/src/images/config.png" width="220" height="115"></a></p>



----------------------------------------------------------------------------------------------------------------------------------------
<h2><b><p align="center">Download files</p></b></h2>
</br>


----------------------------------------------------------------------------------------------------------------------------------------
<h2><b><p align="center"Initialize and upload backend to Heroku</p></b></h2>

<h4><b>1. Sign up for account on Heroku. https://heroku.com/ </b></h4>
<h4><b>2. In your terminal, root folder, run 'npm install'</b></h4>
<h4><b>3. run 'git init'</b></h4>
<h4><b>4. 'git add'</b></h4>
<h4><b>5. 'git commit -m "first commit'</b></h4>
<h4><b>6. 'heroku login'</b></h4>
<h4><b>7. 'heroku create'</b></h4>
<h4><b>8. 'heroku addons:create jawsdb' (To create SQL Manager)</b></h4>
<h4><b>9. 'git push heroku master'</b></h4>

</br>


----------------------------------------------------------------------------------------------------------------------------------------
<h2><b><p align="center">Configure SQL Database for backend</p></b></h2>
</br>

 <h4><b>1. go to app creation on heroku, open 'open app' </b></h4>
 <h4><b>2. You should see this if it worked 'message: "Welcome to the REST API project!"'</b></h4>
 <h4><b>3. Copy and paste the url inside your client folder which is inside your config file in your editor like this and save: </b></h4>
 </br>
 <p align="center"><a><img src="https://github.com/sargef/course-restapi-backend-nodejs-frontend-react-live/blob/master/assets/clientbackendconfigurl.png" width="620" height="300"></a></p>
 </br>
 
 <h4><b>4. While still in the heroku app, select 'resources' from the menu</b></h4>
 <h4><b>5. Select 'Jawsdb mysql'</b></h4>
</br>
 <p align="center"><a><img src="https://github.com/sargef/course-restapi-backend-nodejs-frontend-react-live/blob/master/assets/jawsicon.png" width="620" height="255"></a></p>
 </br>

----------------------------------------------------------------------------------------------------------------------------------------
<h2><b><p align="center">Install HeidiSQL and Setup data tables.</p></b></h2>

<h4><b>1. Install sql platform Heidisql: https://www.heidisql.com/download.php</b></h4>
<h4><b>2. Create the following within heidisql once it is installed</b></h4>
<h4><b>3. Create new database/b></h4>
 
 </br>
 <p align="center"><a><img src="https://github.com/sargef/course-restapi-backend-nodejs-frontend-react-live/blob/master/assets/newdatabase.png" width="620" height="255"></a></p>
 </br>

<h4><b>4. add your credentials from jawsdb to connect to your app</b></h4>
<h4><b>5. Click on open.</h4></b>
<h4><b>6. Save</h4></b>
<h4><b>7. right click on your new database on the left hand side of screen, select create new, then table.</h4></b>

 </br>
 <p align="center"><a><img src="https://github.com/sargef/course-restapi-backend-nodejs-frontend-react-live/blob/master/assets/databasecreate.png" width="620" height="430"></a></p>
 </br>

<h4><b>8. Create 3 new tables like the following and add the same data fields as below.</h4></b>
<h4><b>a. Users (Capital 'U')</h4></b>

 </br>
 <p align="center"><a><img src="https://github.com/sargef/course-restapi-backend-nodejs-frontend-react-live/blob/master/assets/Users.png" width="620" height="215"></a></p>
 </br>

<h4><b>b. Courses (Capital 'C')</h4></b>

 </br>
 <p align="center"><a><img src="https://github.com/sargef/course-restapi-backend-nodejs-frontend-react-live/blob/master/assets/coursesdb.png" width="920" height="455"></a></p>
 </br>

<h4><b>c. sqlite_sequence</h4></b>

 </br>
 <p align="center"><a><img src="https://github.com/sargef/course-restapi-backend-nodejs-frontend-react-live/blob/master/assets/sqlite_sequence.png" width="890" height="215"></a></p>
 </br>


----------------------------------------------------------------------------------------------------------------------------------------
<h2><b><p align="center"></p></b></h2>
</br>


----------------------------------------------------------------------------------------------------------------------------------------
<h2><b><p align="center"></p></b></h2>
</br>


----------------------------------------------------------------------------------------------------------------------------------------
<h2><b><p align="center"></p></b></h2>
</br>


----------------------------------------------------------------------------------------------------------------------------------------



<p align="center">Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.</p>

<p align="center">The build is minified and the filenames include the hashes.</p>
</br>
<h3><p align="center">Your app is ready to be deployed!</p></h3>

<p align="center">See the section about deployment for more information.</p>

<h2>Learn More</h3>
You can learn more in the Create React App documentation.

To learn React, check out the React documentation.

<h3>Code Splitting</h3>
This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

<h3>Analyzing the Bundle Size</h3>
This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

<h3>Making a Progressive Web App</h3>
This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

<h3>Advanced Configuration</h3>
This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

<h3>Deployment</h3>
This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

<h3>npm run build fails to minify</h3>
This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify












