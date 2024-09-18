# E-Commerce-Tech

E-Commerce-Tech is the backend for your e-commerce website! Developed with Express.js, this API uses Sequelize for an easy interaction with a PostgreSQL database. This application offers simple management of products, categories, and tags. 

- you are able to launch your server with a single command. The application will synchronize Sequelize models with the PostgreSQL database automatically.

- Using insomnia and API GET routes, you can view categories, products, or tags  data presented in a well-organized JSON format.

- Insomnia allows you to test API POST, PUT, and DELETE routes, this helps with efficient creation, updating, and deletion of the data in your database.

## Installation

To install CommerceChampion:

- Clone the repository: https://github.com/Justino11247/E-Commerce-Tech

- Go to the project directory

- Launch the terminal execute the following command: `npm install`

- Set up the PostgreSQL database with the following commands:

  - Input `psql -U postgres` to open the PostgreSQL command line interface. If prompted, input your password.
  - To set up the database, type `\i schema.sql` and press Enter.
    Now your database is set up correctly!

- Remove '.EXAMPLE' from the .env.EXAMPLE file renaming it to .env then configure the  file with your database credentials

- Seed data in the terminal by executing the following command: `npm run seed`

## Usage

- Start the application in the terminal by executing the  command: `npm start`

[Link to Walkthrough Video](https://drive.google.com/uc?id=1JQ-Y01yd66TQOIrfAWg3vrkgpS7noYQ6&export=download)

![Screenshot of E-Commerce-Tech](./images/Screenshot%202024-09-17%20181123.png)