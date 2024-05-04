# e-commerce-backend

## Description

This project was created using node.js, express, dotenv, mysql, and sequelize to create the backend of an e commerce web application. Please refer to the installation section for a tutorial on how to interact with the application.

## Table of Contents

-[Installation](#Installation) -[Usage](#Usage) -[Contribution](#Contribution) -[Tests](#Tests) -[License](#License)

## Installation

https://drive.google.com/file/d/1RPtow9Jv0QFH267W8Do7rMYCPqyHZan2/view

## Usage

In order to use this app, you must first install node.js and mysql. After cloning the repository to your system, open an integrated terminal and run "npm install". After installing the dependencies login to mysql by running the command "mysql -u root -p" and enter your password credentials when prompted. Once you have successfully logged in, run the command "SOURCE db/schema.sql" to establish the database. Close out of mysql, and run "node seeds/index.js" in a new terminal. The final step is to correctly set up your .env file with your mysql username and password. After these steps are completed successfully, you can use insomnia to navigate the following links.

- http://localhost:3001/api/products
- http://localhost:3001/api/products/:id
- http://localhost:3001/api/categories
- http://localhost:3001/api/categories/:id
- http://localhost:3001/api/tags
- http://localhost:3001/api/tags/:id

## Contribution

I was provided starter code for this assignment, and established the backend on my own.

## Tests

## License

https://opensource.org/licenses/MIT

## Questions

Please direct questions through my email address

## Contact

jrsevi@gmail.com
