#Web Speech Demo for Wit.

## Prerequisites
* API Token for [Wit](https://wit.ai)
* Node.js (0.8.x+)
* Chrome

## Setup
* Clone repo
* Run ``npm install``

## Usage
* Start the server with ``API_TOKEN=<YOUR API TOKEN HERE, LEAVE OUT THE BEARER> node app.js``
* Point your (Chrome) browser to [http://localhost:3000](http://localhost:3000), click on the microphon icon on the right and speak.

On the console you'll see the API response from Wit.
If you have trained Wit for sentences like "Send $20 to Martin" with the entities "currency", "amount" and "receipient", you'll also see an alert popping up.
