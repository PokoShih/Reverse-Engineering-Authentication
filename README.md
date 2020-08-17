# Reverse-Engineering-Authentication

This application allows user to sign in an create an account.

The sign in details are located in MySQL with the following columns:
id, email, password, createdAt, updatedAt

USER STORY

A company approached a team of web devs for simple sign in application to store data with exisiting/creating accounts.

Dependencies used:
  "dependencies": {
    "bcryptjs": "2.4.3",
    "express": "^4.17.0",
    "express-session": "^1.16.1",
    "mysql2": "^1.6.5",
    "passport": "^0.4.0",
    "passport-local": "^1.0.0",
    "sequelize": "^5.8.6"
  }


Please see following document for more explanations of the application:
