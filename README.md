# How to run this app

To run this app, it needs to be deployed to Cloud Foundry.

## Prerequisites
1. An instance of Document Information Extraction and its service key (you can run [booster](https://developers.sap.com/tutorials/cp-aibus-dox-booster-app.html) to create them automatically)
2. Destination pointing to Document Information Extraction API (Please see [my blog post]() for details)

## Build & Deploy
1. Run `mbt build` to build the app. (* )
2. Run `npm run deploy` to deploy the app to Cloud Foundry.

## Run
In your BTP subaccount, go to "HTML5 Applications" and find "miyasutaui5die".
Click on the link to open the app.  