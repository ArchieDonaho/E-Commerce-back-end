
# E-Commerce Back-End

## Description

This application handles the back-end of an e-commerce site. It contains a database consisting of Products, Categories, Tags, and ProductTags, utilizing the "express", "mysql2", and "sequelize" packages

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)

## Installation

You can install by cloning from this github page

## Usage

* Install all node packages
* Access your mysql database, and run 'source db/seeds.sql' to initialize the database.
* Add your database name (found in db/schema.sql), your MySQL username, and your MySQL password to an environment variable file, and place it in your root directory.
* Ensure that, in the 'server.js' file, where the 'sequelize.sync' function is, the 'force' is set to 'true'.
* Run the server, then close the server. This will initialize the database associations.
* Then set the 'force' in the 'sequelize.sync' function from 'true' to 'false'.
* Seed the database by running 'npm seed'.
* Then run the server to access the database using api endpoints.
* Example of the application in use: https://drive.google.com/file/d/15h6RZupecnKMpejsrxFr3264xVYjYVcC/view

## Questions

Have questions? feel free to reach me here:

archied5150@yahoo.com
https://github.com/ArchieDonaho

