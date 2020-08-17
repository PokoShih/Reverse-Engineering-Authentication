# Reverse-Engineering-Authentication

This application allows user to sign in an create an account.

The sign in details are located in MySQL with the following columns:<br>
id, email, password, createdAt, updatedAt

### USER STORYUSER STORY

A company approached a team of web devs for simple sign in application to store data with exisiting/creating accounts.

### Dependencies USED:
  "dependencies": {<br>
    "bcryptjs": "2.4.3",<br>
    "express": "^4.17.0",<br>
    "express-session": "^1.16.1",<br>
    "mysql2": "^1.6.5",<br>
    "passport": "^0.4.0",<br>
    "passport-local": "^1.0.0",<br>
    "sequelize": "^5.8.6"<br>
  }<br>

### Reverse-Engineering document
Please see following document for more explanations of the application:
https://docs.google.com/document/d/1LYjbPU6KWWpCNQz0UrSm_Fxsomy2eQedewqvIFYPSlU/edit?usp=sharing