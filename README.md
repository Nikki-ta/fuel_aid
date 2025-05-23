# Food Donation Management System

A web application which is useful for management of food donation and collection activities.  
[View Demo](https://food-aid.onrender.com/)

<img src="https://user-images.githubusercontent.com/86913048/226953269-e6ae0484-ab78-4c77-b199-aef793502d8d.png" width="70%">

## Table of Contents

- [Installation and setup](#installation-and-setup)
- [Features](#features)
- [Technologies used](#technologies-used)
- [npm packages used](#npm-packages-used)
- [Prerequisites](#prerequisites)
- [Useful Links](#useful-links)
- [Contact](#contact)

## Installation and Setup

1. Install all the dependencies
   ```sh
   npm install
   ```
2. Create a file named ".env" and enter the following credentials:
   ```js
   MONGO_URI = yourmongouri;
   ```
3. Run the web application
   ```sh
   npm start
   ```
4. Open http://localhost:5000
5. You need to first signup and then login to run the application.

## Features

- The system consists of three types of users: admins, customers and mechanics.
- Admins: They control all the activities and accept/reject donations and select mechanics.
- customers: They are the driving users of the application who donate food.
- mechanics: They are responsible for collecting food from homes of food customers.
- Each user should have an account.
- Every user also have a dashboard where they can view several things in short summary.
- The application provides signup, login and logout functionalities.

### customer Features

- customers make the donation request for food with basic details.
- customers' donation requests can be accepted or rejected and the status can be easily tracked by them.
- customers can view their current incomplete donations (if any).
- customers can also view all their past donations.
- customers can update their profile.

### Admin Features

- Admins receive all the requests made by customers.
- Admins can accept or reject the donation requests depending upon the details provided by a customer.
- If accepted, admins can assign an mechanic to a donation for collecting donation from the customer's home.
- Admins can view all the pending donations along with status.
- Admins can view all the donations that they have received.
- Admins can also view all the mechanics in the application.
- Admins can update their profile.

### mechanic Features

- mechanics will receive notifications from admins to collect food from customer's homes.
- mechanics can mark their collection upon collection of food from customer's home.
- mechanics can also view all those food donations which have been collected by them previously.
- mechanics can update their profile.

## Technologies used

- HTML
- CSS
- Bootstrap
- Javascript
- Node.js
- Express.js
- Mongodb
- ejs

## npm packages used

- express
- ejs
- express-ejs-layouts
- mongoose
- express-session
- bcryptjs
- passport
- passport-local
- connect-flash
- method-override
- dotenv

## Prerequisites

For running the application:

- Node.js must be installed on the system.
- You should have a MongoDB database.
- You should have a code editor (preferred: VS Code)

## Useful Links

- Demo: https://food-aid-aayush.herokuapp.com/
- Github Repo: https://github.com/aayush301/Food-donation-management-system
- Nodejs download: https://nodejs.org/
- VS Code download: https://code.visualstudio.com/
- Tutorials: https://www.w3schools.com/
- npmjs docs: https://docs.npmjs.com/
- Expressjs docs: https://expressjs.com/
- Bootstrap docs: https://getbootstrap.com/docs/5.1/getting-started/introduction/
- Mongoosejs docs: https://mongoosejs.com/docs/index.html
- Mongodb atlas: https://www.mongodb.com/cloud/atlas/register
- Mongodb docs: https://docs.mongodb.com/manual/introduction/
- Nodemailer docs: https://nodemailer.com/
- Github docs: https://docs.github.com/en/get-started/quickstart/hello-world
- Git cheatsheet: https://education.github.com/git-cheat-sheet-education.pdf
- VS Code keyboard shortcuts: https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf
