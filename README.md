  # E-commerce Back End

  ## Table of Contents

  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Preview](#preview)
  - [Contact](#contact)
  - [License](#license)

  ## Description

  A handy back-end tool that allows users to test checking, modifying, and deleting data from a database, involving products with different names, tags, and categories.
  
  ## Installation

  - Ensure that Node.js is installed on your local machine
  - Ensure that MySql is installed on your local machine
  - Ensure that Insomnia is installed on your local machine
  - Clone the GitHub repo to your local machine
  - Modify the ".env.EXAMPLE" file to just be named ".env", and input the MySql credentials into "DB_USER" and "DB_PASSWORD" respectively
  - Use your local machine's command-line to navigate to the cloned repo's directory
  - Using either MySql Workbench or the MySql shell, run the schema.sql file and then return to the normal command-line of your choice
  - Run "npm install"
  - If you want to utilize the given seed data, run "npm run seed"
  - Run "npm start"
  - Perform tests using Insomnia (see [preview video](#preview) for reference)

  ## Usage

  This application is run entirely on back end technology to easily enable a user to test hypothetical API routes to view information on a selection of products, with a testing seed provided to check the routes in action without needing to input new data on their own. After modifying the .env file included in the repository, the user may connect to the repo's proposed database using the MySql shell/workbench and Sequelize. After initializing both the built-in schema and seeds files, the user may then utilize Insomnia to view API GET, POST, PUT and DELETE routes to modify the database's information as they see fit.

  ## Preview

  [Check out this link for a video recording of the application in action.](https://drive.google.com/file/d/1XRjtbU2TSNgUSg3GWCeLKMyirP6Hvlnd/view)
  
  ## Contact

  - Github: [Darxmarx](https://github.com/Darxmarx)

  ## License

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)