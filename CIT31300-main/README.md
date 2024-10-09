# Project Title
This project is a Coffee Shoppe group project by Andrew, Tyler, and Ryan. We assumed a small business in Indiana wanted a prototype suite of web pages that displayed their coffee shoppe products.

# Main features
The main features of our project were creating a relational database that had an inventory of at least 10 products. We also created a cards based layout to display images of these products. There were buttons added to each card that would show the price and availability of each product. The design of the webpages was done using Bootstrap.

# Installation
To setup the project on your local system, you will need to install npm, express, ejs, sqlite3, and sqlite. To do this you can use the following in your IDE's terminal:

npm init --y
npm install express ejs
npm install sqlite3 sqlite
npm install nodemon

Once all of these packages have been installed you will need to go into package.json and add the following after the package name:
"type": "module",

To run the application enter the following:

node app.js

You will then open a browser of your choosing and paste the following:

http://localhost:3000/

You will then be able to click on the routes that we have setup and test all of the features that have been listed above.
