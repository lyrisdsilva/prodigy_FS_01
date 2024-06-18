# Task-01-Full Stack Web Development internship at Prodigy InfoTech 

# Project Overview
Excited to announce the successful completion of Task-01 during my full stack web development internship at Prodigy InfoTech 🚀. the project involved creating a user authentication
system with secure login and registration functionality. 

# Table Content
1. [Project Description](#project-description)
2. [Technologies Used](#technologies-used)
3. [Setup and Installation](#setup-and-installation)
4. [Project Structure](#project-structure)
5. [Contributors](#contributors)

## Project Description
Task-01 Secure User Authentication
Implement a user authentication system with secure login and registration functionality. Users should be able to sign up for an account, log in securely, and access protected routes only after successful authentication. Use standard mechanisms to handle password hashing, session management, and user role-based access control. Protected routes should restrict unauthorized access to sensitive functionalities.

## Objectives
* System with secure login and registration functionality.
* Mechanisms to handle password hashing.
* Protected routes should restrict unauthorized access.

## Technologies Used
* Reactjs: Used for user interfaces, particularly for single-page applications where data can change over time.
* Nodejs: Node.js is a runtime environment that allows you to run JavaScript code outside of a web browser.
* npm: Node Package Manager is the default package manager for Node.js, used to manage dependencies and packages for JavaScript projects.
* MongoDb: open-source NoSQL database management system that uses a document-oriented data model
* Bcrypt: hashing algorithm designed specifically for password hashing.
* JWT: JSON Web Token, It is a compact URL-safe means of representing claims to be transferred between two parties.

## Setup and Installation
### Prequisites
Ensure that you have the following software installed:
* VScode(latest or higher)
* Reactjs
* Nodejs and npm
* MongoDb, Bcrypt, jwt
### Running the Task
1. Open the folder
   ```bash
   cd path
   cd projectname
   ```
2. To start the Frontend
   ```bash
   cd client
   npm run dev
   ```
  client works on [http://localhost:5174/] 
  
3. To start the Backend
   ```bash
   cd server
   npm start
   ```
server works on [http://localhost:8000/] 

After this commands are used the task is connected to the database you are ready to go.

## Project Structure
```bash
├── README.md 
├── .gitignore
├── client/ # Frontend 
│    ├── context/
│    ├── index.html
│    ├── node_modules/
│    ├── package-lock.json
│    ├── package.json
│    ├── public/
│    ├── README.md
│    ├── src/
│    └── vite.config.js
├─── server/ # Backend
│    ├── controllers/
│    ├── helpers/
│    ├── index.js
│    ├── models/
│    ├── node_modules/
│    ├── package-lock.json
│    ├── package.json
└──  └── ruotes/
```

## contributor
* Lyris Dsilva - [lyrisdsilva@gmail.com]
* Linkedln - https://www.linkedin.com/in/lyris-dsilva-a23b94216/  
Feel free to reach out with any questions or feedback!


Thank you for your interst in this project.
Happy Coding! 🥳
