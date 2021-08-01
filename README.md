# Contact Management System

In this web application, a user can create, view and delete the contacts. Basically, CRUD (Create, Read, Update, and Delete) operations are followed. 


## Demo
Contact Management System



<p> <img align="center" alt="gif" src="https://github.com/harshh351998/Contact-Management-System/blob/main/demo.gif" width ="900" height ="520" /> </p>




## Technology Stack

1. Nodemon ( nodemon is a tool that helps develop node. js based applications by automatically restarting the node application when file changes in the directory are detected)
2. Express ( Express. js is a free and open-source web application framework for Node. js. It is used for designing and building web applications quickly and easily. )
3. Body Parser ( The bodyParser object exposes various factories to create middlewares. )
4. Dotenv ( Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env )
5. Morgan ( It is s a HTTP request logger middleware for Node. js. It simplifies the process of logging requests to your web application. )
6. Mongoose ( Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node. js )
7. Axios ( It is  is a promise based HTTP client for the browser and Node.js )
8. EJS ( EJS is a simple templating language which is used to generate HTML markup with plain JavaScript. It also helps to embed JavaScript to HTML pages. )
9. CSS ( Cascading Style Sheets are used for styling the ejs template pages.

## Project Architecture

This project follows MVC ( Model-View-Controller ) architecture pattern that separates an application into three main logical components.
a) In model section, the mongo-db database model is created.
b) In view section, front-end development is done with help of ejs template and css for styling purpose.
c) In controller section, following operations of application like create, view, and delete are developed.

## Database Creation

In this project I had Mongo db database which is document based unstructured type.In this project I have stored my data in free aws cloud not in localhost. Steps for setting up database.
1) Go to the following website, https://www.mongodb.com/
2) Sign up with your google account.
3) Create new project and give any name for ex:- Contact, CRUD, and so on.
4) After creating new project, click on build cluster option.
5) Select free aws cluster with mumbai region and create it.
6) On left side tab, click on Database Access and click on Add Database user option.
7) In password authentication section, specify admin for username and admin123 for password. Click on add user button.
8) Now click on Network Access option, which is present on left side tab below Database Access.
9) Click on Add IP Address option. Select other option, "allow access from anywhere" and click on confirm button.
10) Go back to cluster and click on connect option. Select the option, "connect your application".
11) Copy the connection string url and paste on the project file name," config.env". 
              
              
 ## Steps for running this web application.
 
 1) Download this project and open in VS code editor.
 2) Run the following command npm install
 3) Then setup the database by following steps of database creation.
 4) Run the final command npm start for running the server.
 5) Perform the CRUD operations on the user contacts.
