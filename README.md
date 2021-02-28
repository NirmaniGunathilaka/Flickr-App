# Flickr Feed Viewer and Search 

Simple web application that reads data from Flickr's public feeds and displays the images on the page to the user.

## General Info

On page load the applications should load the public feed images in either a list or grid view. • The user should be able to enter a keyword in a search box and click on a search button and the app should return images with the relevant tags.
Flickr API has used as the 3rd party API.

Public Feed : "https://api.flickr.com/services/feeds/photos_public.gne?format=json&nojsoncallback=1"
Search      : "https://www.flickr.com/services/rest/?method=flickr.photos.search&api_key="+apikey+"&tags="+value+"&format=json&nojsoncallback=1"

## Technologies
Frontend - Reactjs
Backend - Nodejs, Expressjs

## Setup

### Backend
$ cd flickr-app
$cd backend
$ npm install
$ nodemon server

### Frontend
$ cd flickr-app
$npm start

