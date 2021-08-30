# authentication-app
Built With
Node.js - JavaScript runtime built on Chrome's V8 JavaScript engine.
Express.js - Minimal and flexible Node.js web application framework
MongoDB - Cross-platform document-oriented database program

Getting Started
To get a local copy up and running follow these simple steps :

Prerequisites
-To run this project, you'll need to have the following installed:

--Node.js : https://nodejs.org

--npm :

npm install npm@latest -g
--MongoDB : https://mongodb.com

You can also use MongoDB Atlas if you prefer.

-Installation
1.Register at SendGrid SendGrid and create an API KEY.

2.Clone the repo :

--git clone https://github.com/Shikha-code36/authentication-app.git
3.Install dependencies (use sudo if required) :

npm install

4.Create .env file and configure :

MONGO_URI = <MONGODB_URL>
JWT_SECRET = <SOME_LONG_SECURE_SECRET>
SG_APIKEY = <SENDGRID_API_KEY>  //For sending emails
Start the server :

npm start