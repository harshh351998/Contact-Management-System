# Contact Management System

In this web application, a user can create, view and delete the contacts. Basically, CRUD operations are followed. 

## Technology Stack

1. Nodemon
2. Express
3. Body Parser
4. Dotenv
5. Morgan
6. Mongoose
7. Axios
8. EJS

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
11) Copy the connection string url and paste on the project file name," config.env". See the sample.
              MONGO_URI = mongodb+srv://admin:admin123@crud.zupxf.mongodb.net/CRUD?retryWrites=true&w=majority    
              
              
 ## Steps for running this web application.
 
 1) Download this project and open in VS code editor.
 2) Run the following command npm install
 3) Then setup the database by following steps of database creation.
 4) Run the final command npm start for running the server.
 5) Perform the CRUD operations on the user contacts.
