# MERN Stack Job Finder Application

## Overview

Welcome, coders! This is the final session of our MERN Stack project. In this session, we will guide you through integrating the frontend and backend of our Job Finder application using MongoDB, ExpressJS, ReactJS, NodeJS, and Tailwind CSS for styling the user interface. After completing the integration, we will show you how to deploy the application to the internet.

## Get Started

### Backend (Server)

1. **Navigate to the Server Directory**
   - Move to the server directory using the command: `cd server`

2. **Create a .env file**
   - Create a `.env` file in the server directory and add the following variables:
      i. `MONGODB_URL` = `database connection string`
      ii. `JWT_SECRET_KEY` = `your secret key`
      iii. `PORT` = `8800`
      iv. `AUTH_EMAIL` = `email address`
      v. `AUTH_PASSWORD` = `email access password`
      vi. `APP_URL` = `http://localhost:8800/api-v1`

      Note: We recommend using a Hotmail account to send verification emails, as it is reliable and requires no additional configuration. Also, remember to change `APP_URL` when deploying your app, or use localhost with the appropriate port number.

3. **Install Dependencies**
   - Run `npm install` to install the required packages.
   
4. **Start the Server**
   - Run `npm start` to start the server on `http://localhost:8800`

### Frontend (Client)

1. **Create a .env file**
   - In the root folder of the client, create a `.env` file and add an environment variable named `REACT_APP_CLOUDINARY_ID`. This variable will store the Cloudinary cloud name.

2. **Install Dependencies**
   - Run `npm install` to install all client-side dependencies.

3. **Start the Client**
   - Run `npm start` to start the client on `http://localhost:3000`

Now you're all set! Happy coding and building your MERN Stack Job Finder application.