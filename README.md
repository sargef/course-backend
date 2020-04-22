Course - restAPI - Backend (Nodejs) Frontend (React)
 
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











<h1><b><p align="center">React App Api Image Search</p></b></h1>


<h3><b><p align="center">Click to see live Course App!!</p></b></h3>
<a href="https://course-restapi-38.herokuapp.com/" target="_blank"><img src="https://github.com/sargef/course-restapi-backend-nodejs-frontend-react-live/blob/master/assets/course.png"></a>

<h2><b><p align="center">React App</p></b></h2>

<h1><p align="center"> :sparkles: This react app will require the following config to be hosted online :sparkles: </p></h1>
<br />

<h4><b>1. </b></h4>
<h4><b>2. </b></h4>
<br />

<br />
<br />
<h4><b>3. </h4></b>

<p align="center"><a><img src="https://github.com/sargef/react-app-api-image-search/blob/master/src/images/config.png" width="220" height="115"></a></p>



<h4><b>4. Run npm install in the root of the project.</h4></b>
<h4><b>5. npm start.</h4></b>
<h4><b>6. View on localhost port 3000 as suggested inside your terminal.</h4></b> :+1:
<br />
<br />
<br />


<h2><b><p align="center">Create React App references below;</p></b></h2>
</br>

----------------------------------------------------------------------------------------------------------------------------------------
<h2><b><p align="center">npm start.</p></b></h2>
</br>


<p align="center">Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.</p>

<p align="center">The page will reload if you make edits.
You will also see any lint errors in the console.</p>

----------------------------------------------------------------------------------------------------------------------------------------
<h2><b><p align="center">npm test.</p></b></h2>
</br>


<p align="center">Launches the test runner in the interactive watch mode.
See the section about running tests for more information.</p>

----------------------------------------------------------------------------------------------------------------------------------------
<h2><b><p align="center">npm run build.</p></b></h2>
</br>

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












