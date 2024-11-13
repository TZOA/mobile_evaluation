# Mobile Evaluation
Test for evaluating mobile developers.

# Overview
The purpose of this test is to evaluate potential mobile developers.  A simple mobile app will created.  The app is a version checker.  Our mobile app uses a static file on a webserver to determine the current version of our apps.  The app to be written will download the version file and display it to the user.

# Details
The app will consist of two pages.  The first page the user selects which development environment they want to use.  Once they choice is made, the environment is passed to the second page.  On the second page the app will fetch the file, parse it and display the result to the user.  The images provided give a general idea of how the app should work and look.

The version files for the different environments are:
- https://s3.us-west-2.amazonaws.com/static.haveniaq.com/app-version/version-dev.json
- https://s3.us-west-2.amazonaws.com/static.haveniaq.com/app-version/version-staging.json
- https://s3.us-west-2.amazonaws.com/static.haveniaq.com/app-version/version-production.json

There will have to be assumptions made about the app.  Please write all of these down.  Also track the time spent on the app.  The end result should be an app that we can build and run to test.
