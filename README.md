# Flask-HelloWorldBot
A Basic Template for A FB Messenger Bot created in Flask


Steps to get up and running:

1) Read this: https://developers.facebook.com/docs/messenger-platform/quickstart and follow steps (not including node.js stuff)

2) Replace <ACCESS_TOKEN_HERE> with the actual access token you got

3) Replace <VERIFY_TOKEN_HERE> with whatever veryify token you will be using

4) Host this somewhere, you need an https URL so I reccommend Heroku if you don't want to deal with that. This should (I think) work with heroku out of the box so https://devcenter.heroku.com/articles/getting-started-with-python#introduction 

5) Finish setting it up (The URL to setup the webhook is /setup and the URL you want to actually receive messages at is /webhook). So the first time it asks you for a URL to set it up ("Verify and Save") use YOUR_URL + '/setup' and when you actually want to start receiving/sending messages use YOUR_URL + '/webhook'

6) If you did it correctly, your page should respond to every message from YOU to the page with "Hello World" 
Note that this will not work for anyone else until you submit your app for review

I don't have much more experience with bots than this, but I would be happy to try and answer any questions you have! You can contact me at reparadocs (at) gmail (dot) com
