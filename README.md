# Overview
 Using reactjs and redux web billing app has been created. Registered person can login and add products, customers and create bills.Finally the bills can be downloaded as pdf.
 
# Tech Stack
JavaScript |ES6
React JS,Redux and redux-thunk
Git

# Packages
  "antd": "^4.16.13",
  "axios": "^0.21.1",
  "bootstrap": "^5.1.0",
  "formik": "^2.2.9",
  "jspdf": "^2.3.1",
  "moment": "^2.29.1",
  "react": "^17.0.2",
  "react-calendar": "^3.4.0",
  "react-dom": "^17.0.2",
  "react-google-charts": "^3.0.15",
  "react-paginate": "^7.1.3",
  "react-redux": "^7.2.4",
  "react-router-dom": "^5.2.1",
  "react-scripts": "4.0.3",
  "reactstrap": "^8.9.0",
  "redux": "^4.1.1",
  "redux-thunk": "^2.3.0",
  "yup": "^0.32.9"

# FEATURES

# Authentication

# User registration and login
* JWT is maintained for authentication

# Custom form validation

# Customer

The logged in user can add customers by providing name, mobile number and email.
The customer details can be viewed as well as edited.
The customer can also be deleted but it is not recommendable to delete a customer.

# Product

The user can add products providing product name and price.
The product details can be edited.
The product can also be deleted but it is not advisable to delete product.

# Bills

The user can create bill for a customer by providing date.
The products can be selected from the checkbox.The quantity can be incremented or decremented,by default quantity is set to 1.
Once added to cart, user can add other products also.
The products can be removed from the cart.From the cart bills can be generated.
Once the bill is generated, the bill can be downloaded as pdf.
The generated bill can be viewed as well as deleted.

# Dashboard

All the total number of customers, products, bills are provided.
Pie chart is implemented for showcasing customers,products,bills.

# Author
Soram Wanglen
