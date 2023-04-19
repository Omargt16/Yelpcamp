# Yelpcamp
This is an application built to manage campgrounds around the world 
```npm
npm init 
npm start
nodemos app.js
```
To run this application locally is necessary to add the .env file to the main folder and include the following variables
```dotenv
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_KEY=
CLOUDINARY_SECRET=
MAPBOX_TOKEN=
PORT=
```
Also it is necesary to add the username into the url that is in helmet.contentSecurityPolicy in the field imgSrc
