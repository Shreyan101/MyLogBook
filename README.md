

## LogBook
Logbook is a Web-Application where information is recorded 
for review and tracking. It is used in the workplace to keep track
of events, actions- and many other things.

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/frontPage.png?raw=true)

## Features
&#8594; Register

This website has a feature for user to register. We have created 
a Database Users and a database table UserSchema. We have used 
MongoDB, Mongoose for database connection.

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/Register.png?raw=true)

A registration form is created with react and user have to fill 
all the information in that form in order to register.
Name, Email, Phone, Profession, Password, CPassword.


![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/register2.png?raw=true)

If user is registered successfully then a popup comes on screen 
which shows user registered successfully and Login Screen appears to user for login.

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/register3.png?raw=true)


This website has a feature for user to register. We have created 
a Database Users and a database table UserSchema. We have used 
MongoDB, Mongoose for database connection.



&#8594;  const mongoose = require('mongoose');

&#8594;  const DB = process.env.DATABASE;

&#8594;  mongoose.connect(DB, {
    useNewUrlParser: true,
    useCreateIndex: true,
    useUnifiedTopology: true,
    useFindAndModify:false
}).then(() => {
    console.log(`connnection successful`);
}).catch((err) => console.log(`no connection ${err}`));


![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/mongodb_registerstore.png?raw=true)



&#8594; Login

After Successfully Registering the user information is stored in the database and the user is directed to login page.
There is Login option in website if user is already registered the user can login.


![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/Login.png?raw=true)

User have to give Email and Password in order to login and if
 they successfully login then a popup appears which says user 
 login successfully and the user is directed to Home page where
  User name is displayed.

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/login_user.png?raw=true)

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/login_user2.png?raw=true)

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/after_userLogin.png?raw=true)

&#8594; Contact

A contact page is there where user can send message regarding 
any issues. User message is stored in database.


![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/contact.png?raw=true)

&#8594; About

User have to first login inorder to view About Page. 
Once the user login then the page is directed to About page.

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/AboutWithoutLogin.png?raw=true)

In About Page The user name is displayed and all the information 
about user is displayed there. 

&#8594; USER Id

&#8594; Name

&#8594; Email

&#8594; Phone

&#8594; Profession

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/user_aboutme.png?raw=true)


## Tools Used

&#8594; MongoDB

&#8594; Express. js

&#8594; React. js

&#8594; Node. js


&#8594; MongoDB: A popular NoSQL database. It stores data in JSON 
format.

&#8594; Express. js: A flexible and minimal web framework for Node

&#8594; React. js: A JavaScript library used to create user-interfaces.

&#8594; Node. js: Node. js (Node) is an open source development
platform for executing JavaScript code server-side.

## Screenshot

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/frontPage.png?raw=true)

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/Register.png?raw=true)

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/register2.png?raw=true)

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/register3.png?raw=true)

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/mongodb_registerstore.png?raw=true)



![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/Login.png?raw=true)

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/login_user.png?raw=true)

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/login_user2.png?raw=true)

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/after_userLogin.png?raw=true)


![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/contact.png?raw=true)

![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/AboutWithoutLogin.png?raw=true)




![App Screenshot](https://github.com/Shreyan101/MyLogBook/blob/master/images_screen/user_aboutme.png?raw=true)



