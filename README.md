## Description
Tech Blog is proof of concept challenge project for UC Berkeley bootcamp. The requirement was to build a content management system (CMS) style blog where users can create, edit, and comment on technology blog posts. It follows a Model View Controller (MVC) paradigm architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

## Table of Contents
* [Installation Requirements](#install)
* [NPM Packages Used](#npm)
* [Application Usage](#usage)
* [Questions](#questions)


## <a name=install></a>Installation Requirements


### <a name=npm></a>NPM Packages
* mysql2
* dotenv
* express
* sequelize
* bcrypt
* express-handlebars
* express-session

***
## <a name=usage></a>Application Usage
The application can be cloned from github using:
```
git clone 
```
In order to properly connect the application with a MySQL databaase a .env file must be created and populated with the appropriate information including your database password:

```
DB_NAME='Tech_Blog_db'
DB_USER='root'
DB_PW='<your password>'
```
Once all of the dependencies are installed, the database can be built and seeded using the following commands. The first should be executed in the mysql CLI, and the second in node terminal. 
```
source db schema.sql
npm run seed
```
To run the application, from root use:
```
npm start
```

## Questions
Any questions or feedback regarding this project can be sent directly to my email, fkobe3@gmail.com, or through github, my username is fkobe3.
