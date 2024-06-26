# Pakwaan Restaurant Server

This repository contains the server-side code for the Pakwaan Restaurant web application. The server handles all the backend functionalities, including user authentication, CRUD operations for menu items, and administrative controls.

## **Project Purpose**

This server was created as part of a homework assignment for the **Programming Hero Stride** program. It enables users to **add**, **edit**, and **delete** menu items, demonstrating the implementation of CRUD (Create, Read, Update, Delete) operations. This functionality allows the **Programming Hero homework checker** to verify that the required features are implemented and working correctly. Additionally, the system has **admin capabilities** to manage these operations.

## **Features**

- **User Authentication:** Secure user login and registration.
- **CRUD Operations:** Users can create, read, update, and delete menu items.
- **Admin Controls:** Admin users have special permissions to manage the entire menu.
- **Error Handling:** Graceful handling of errors with meaningful messages.
- **Security:** Implemented measures to protect against common vulnerabilities.

## **Technologies Used**

- **Node.js**
- **Express**
- **MongoDB**
- **JWT (JSON Web Tokens)**
- **Axios**

## **Installation**

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/pakwaan-restaurant-server.git
   cd pakwaan-restaurant-server
  npm install
## **Configuration**
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
## **Usage**
nodemon index.js

