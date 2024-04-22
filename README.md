# Reel Radar Reviews

 ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

## Description

A site to write about tech in a blog format. Defenitly not to review movies

## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Features](#features)
- [Questions](#questions)

## Installation
These steps are for if a user wishes to download the repo and run the application on their own local server.

*Note 'postgres' and 'password' are the default PostgresSQL username and password, if the user has a different username or password, then the 'postgres' and 'password' in step 3 must be adjusted accordingly. Additionally, the user must set the values in their ``.env`` file, in step 2..

1. Download, copy, or clone the code to your local machine through GitHub and open in VSCode, or another appropriate IDE. 

2. The user must setup a .env file with the following:

    ```DB_NAME='moviereview_db'```

    ```DB_USER="postgres"```

    ```DB_PASSWORD="password"```

3. Right click on 'server.js' and select 'Open In Integrated Terminal', then run the command ```npm install``` to install all required node files. 

4. The user must then launch Postgres by running the command: ```psql -U postgres```, in the terminal then running the command: ```password```. 

5. Continue in the terminal by running the command: ```\i db/schema.sql```, to initialize their database, then run the command: ```\q```, to exit PostresSQL.

6. Once out of Postgres the user can run the command: ```npm start```, to launch the application.

## Usage

Application link: https://reel-radar.onrender.com/

Once inside the webpage, the User can create and account, or if they already have an account, they can login. 

The main functionality of our webpage is writing a blog which can be accessed by clicking the "write a blog" button, where the user will be brought to a new page where they can write a blog.

Once submitted The blog view will appear on the homepage, profile, and search results. 

If clicking the profile button in the top right, the user will be taken to their individual profile, where the user can edit their personal information, and blogs. 

Clicking the home button in the top right, takes the user back to the homepage. At the bottom of the homepage the user can search for other users. 

The search user page will show a users profile sans their personal information and has no options to edit

## Credits

Movie API data: https://www.themoviedb.org/

Select UI elements from: https://uiverse.io/

Header Style from: https://codepen.io/


## Features

This application boasts the integration of a PostgressSQL databases into JavaScript, through the use of Seqelize. Additionally, this application features the ability to perform a variety of POST, GET, PUT and DELETE requests to multiple tables and models within our database. Also implemented is emai.js to send sign-up emails to new users.

## Questions

Any questions please reach-out to any of our e-mails at: 

* samuelfullerca@gmail.com

