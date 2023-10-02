# Bookshelf API

A simple CRUD API to manage the list of books.

Created with Node.js and Hapi.js.

## Run this project

Before run this project in directory, don't forget to run `npm install`.

In the project directory, you can run:

### `npm start`

This program will run on [http://localhost:9000](http://localhost:9000).

### `npm run start-dev`

Same as `npm start`, but this program will run with using nodemon.

### `npm run newman-test`

This will run the test script to perform API testing.

## Postman configuration

### Import collection and environment

In your postman application, import the collection and environment from "BookshelfAPITestCollectionAndEnvironment" folder, 
by clicking "Import" button and upload the file which has been provided on that folder.

### Run the tests

To perform API testing, you can click "Run Bookshelf API Test" in the collection, and then it will run all the entire tests. 
(Alternatively, you can just run the tests in your project with [npm run newman-test](#npm-run-newman-test))
