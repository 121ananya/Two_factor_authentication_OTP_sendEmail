# Welcome to Email OTP Authentication Login System

Hello everyone, In this project, we are going to create **EMail OTP Authentication Login System**. 
We will take a look at how to create login, registration, profile, reset password routes and learn
how to send Mail from the Node.js backend application.

## Working with the Project

Download this project from above link.Perform npm i to install related dependencies in package.json and run npm start for runinnig nodemon server.



After that create a file in the Server Folder with the name config.js and put the below code inside it.

config.js
```
export default {
    JWT_SECRET : "<secret>",
    EMAIL: "steve.franecki@ethereal.email", // testing email & password
    PASSWORD : "sMf46xCzrvdrxvuagc",
    ATLAS_URI: "<MONGODB_ATLAS_URI>"
}
```

> **Note:** The **ATLAS_URI** is important to work this project.

Now, create all these variables in the project and make sure you set ATLAS_URI variable.
Otherwise, the project will not work.

# Two_factor_authentication_OTP_sendEmail
