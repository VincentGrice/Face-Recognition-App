# Face Recognition React App
This app will allows you to upload a face image from the image's url or address. You will paste it in the detect box and the Face recognition API will detect the face of person in the image with a box, but first you must register before you can sign in. Try it out !

## Cloning App 
* Open your terminal and clone
git clone "this repositories url"
*Run command in terminal while in this repository
$ npm start

## Getting Started
*Make sure you create a react app*
You can start your own react app following the instructions here
https://reactjs.org/docs/create-a-new-react-app.html

# Make sure yo have nodejs downloaded
https://nodejs.org/en/download/

## Dependencies
## Bcrypt for secruing passwords https://www.npmjs.com/package/bcrypt
```
npm install bcrypt
```
*In your API*
```
const bcrypt = require('bcrypt');
```
## Body Parser https://www.npmjs.com/package/body-parser
```
 npm install body-parser
```
*In your API*
```
var bodyParser = require('body-parser')
```
## Clarifai face detection https://clarifai.com/models
*Find the face detection model and follow the instructions for it. *

## Cors https://www.npmjs.com/package/cors
```
npm install cors
```
*In your API*
```
var cors = require('cors')
```
## Express https://www.npmjs.com/package/express
```
npm install express
```
*In your API*
```
var express = require('express')
```
## Knex https://www.npmjs.com/package/knex
*In your API*
```
var knex = require('knex')
```
## PG https://www.npmjs.com/package/pg 
```
npm install pg
```

## Visit my application live
*You will need to register when the app comes up with an email and password. After that you will be able to log in. Once you're logged in you will need to choose any picture with a url and you will paste this url into the detection box. There will be a blue box that shows up around the face of the person in the image. This is done by using the claifai face detection api. 

https://genius-grice.herokuapp.com/
