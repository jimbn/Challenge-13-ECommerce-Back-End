# ECommerce-Back-End

  ![badge](https://img.shields.io/badge/license-MITLicense-brightorange)
  
  ## Table of Contents
  
-[Licensing](#Licensing)

-[Description](#Description)

-[Demo](#Demo)

-[Installation](#Installation)

-[Usage](#Usage)

-[Tests](#Tests)

-[Questions](#Questions)

  ## Licensing:
 
  This application uses MIT License.

  For more information please visit the [license description](https://choosealicense.com/licenses/mit/).

  ## Description

  ECommerce-Back-End built using Express.js API and configured to use Sequelize to interact with a MySQL database.
  
  
  ## Demo 

[Link to Full Walkthrough Video ] (https://drive.google.com/file/d/1CzrsJ4rZ6J-TgFKaoqBnsA_KQdvS4kyt/view)

  ## Installation
  To install this application:
    - Clone the application repo into local machine and then in the root directory , enter into the terminal :
        - 'npm init -y' 
        - 'npm i sequelize mysql2 dotenv'
        - make sure INSIDE PACKAGE.JSON scripts looks like the following  
            "scripts": {
                "test": "echo \"Error: no test specified\" && exit 1",
                "start": "node server.js",
                "seed": "node seeds/index.js"
            }

  ## Usage 
  Instructions for use:
    - Open MySQL powershell with 'mysql -u root -p'.
    - In MySQL powershell enter the following: 
        - 'source db/schema.sql;' (to source datebase with schema file)
        - 'show databases;' (Make sure ecommerce_db is added)
        - 'use ecommerce_db;' (Use that database)
        - 'quit' (Exit from MySQL powershell)

    - In the terminal enter the following:
        - 'npm run seed' (Start the server)
        - 'npm start' 

    - Open Insomnia/Postman to begin testing the routes found in routes directory 
 

  ## Tests 
  Instructions for testing this application:

  Users  can test the  API  routes by entering them into  Insomnia/Postman after seeding the database and starting the server .

  ## Questions
  Any questions please reach out to me at my [Github](https://github.com/jimbn)

