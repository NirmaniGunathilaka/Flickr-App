# Flickr Feed Viewer and Search 

Simple web application that reads data from Flickr's public feeds and displays the images on the page to the user.

# Table of Contents

[General Infro](## General Info)
## General Info

This is an full stack application that can be used to load the public feed images of the API as a grid view and also to search images which returns from the API by giving a keyword.

Flickr API has used as the 3rd party API.

* Reads the Flickr's public feed

* Search images


Public Feed : "https://api.flickr.com/services/feeds/photos_public.gne?format=json&nojsoncallback=1"

Search      : "https://www.flickr.com/services/rest/?method=flickr.photos.search&api_key="+apikey+"&tags="+value+"&format=json&nojsoncallback=1"

## Technologies

Frontend - Reactjs 

Backend - Nodejs/Expressjs [v10.16.3]

## API Testing

Jest

## API Methods

api/photos       : load the public feed images

api/search/[tag] : returns the images which is match with the relevant tag.

## Setup

### Backend

$ cd flickr-app

$cd backend

$ npm install

$ nodemon server

### Frontend

$ cd flickr-app

$npm start

