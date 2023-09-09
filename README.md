# MERN Stack E-commerce Website

Welcome to the MERN Stack E-commerce Website project repository. This project is an example of a full-stack e-commerce application built using the MERN stack.

![Project Screenshot](screenshot.png)

## Table of Contents

- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)



## About

This e-commerce website allows users to browse products, add them to their cart, and complete the purchase process. It also includes user authentication and a dashboard for administrators to manage products, orders, and users.
We have made an admin with set to role : 1 in mongodb database   
- Admin- admin@gmail.com
- password - 1234567890
-if u are using ur own database ,change a role to 1 from database for admin.its is by default 0(role) for user.
## Features

- User authentication (signup, login, and logout)
- Product catalog with categories
- Product search and filtering
- Shopping cart management
- Checkout and order history
- Admin dashboard for product and user management
- Secure payment processing (you can specify the payment gateway used)
- Responsive design for mobile and desktop

## Technologies Used

- **Frontend**:

  - React.js
  - UseContextApi hook for state management
  - React Router for navigation
  - Axios for API requests
  - Bootstrap and Ant design for UI components (choose one)
  - react-toastify for notification
  - react-helmet to update meta tags

- **Backend**:

  - Node.js
  - Express.js
  - MongoDB for database storage
  - Mongoose for object modeling
  - JSON Web Tokens (JWT) for authentication
  -

- **Payment Gateway**:

  - Braintree Payment gateways

- **Deployment**:
  - Cyclic.sh

- **Installation**:
  1. Clone the repository: `git clone https://github.com/Komal-Dubey/Ecommerce-Mern`
2. Install server dependencies: `npm install`
3. Install client dependencies: `cd client && npm install`
4. Configure environment variables.
5. Start the server: `npm run server`
6. Start the client: `npm run client`


  Note - if u have any proxy error please comment any line on frontend in src folder.and then uncomment it.
