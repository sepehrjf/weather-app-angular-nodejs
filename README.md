# Angular Weather Web App
An Angular weather web application with a backend of Node.js hosted on Google Cloud App Engine.

Click **[HERE](https://csci571-homework-8-330206.wl.r.appspot.com/)** to view it live.

This is a detailed web app that uses a few APIs to fetch the weather info based on the user’s location. 
The location can be searched manually by typing the address using Google Geolocation API or automatically by the user’s current location through IP info. 
The data for the weather will be fetched using an API from a website called [Tomorrow.io](https://www.tomorrow.io/) in the form of a JSON file. 
Then, the data will be shown on a table, visualized on two charts.

# Quickstart for Node.js in the App Engine standard environment

This is the sample application for the
[Quickstart for Node.js in the App Engine standard environment][tutorial]
tutorial found in the [Google App Engine Node.js standard environment][appengine]
documentation.

* [Setup](#setup)
* [Running locally](#running-locally)
* [Deploying to App Engine](#deploying-to-app-engine)
* [Running the tests](#running-the-tests)

## Setup

Before you can run or deploy the sample, you need to do the following:

1.  Refer to the [appengine/README.md][readme] file for instructions on
    running and deploying.
1.  Install dependencies:

        npm install

## Running locally

    npm start

## Deploying to App Engine

    gcloud app deploy

## Running the tests

See [Contributing][contributing].

[appengine]: https://cloud.google.com/appengine/docs/standard/nodejs
[tutorial]: https://cloud.google.com/appengine/docs/standard/nodejs/quickstart
[readme]: ../../README.md
[contributing]: https://github.com/GoogleCloudPlatform/nodejs-docs-samples/blob/main/CONTRIBUTING.md
