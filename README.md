

# 🛒 MERN eCommerce Website

## 📌 Overview
This is a fully functional **eCommerce website** built using the **MERN (MongoDB, Express.js, React, Node.js) stack**. It includes **client and admin pages** with **secure password encryption**.

Created by following a tutorial

## 🚀 Features
- **User Authentication** (JWT & bcrypt encryption)
- **Admin Dashboard** for managing products, orders, and users
- **Product Listings, Search & Filtering**
- **Cart & Checkout System**
- **Payment Integration (PayPal)**
- **Responsive Design**

## 🛠️ Tech Stack
- **Frontend:** React, Redux,Tailwind
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT, bcrypt
- **Deployment:** (Vercel, Netlify, or Heroku)

## 📂 Project Structure
```plaintext
/ecommerce-project  
│-- /client  (React Frontend)  
│-- /server  (Node.js & Express Backend)  
│   │-- /models  (MongoDB Schemas)  
│   │-- /routes  (API Routes)  
│   │-- /controllers  (Logic for routes)  
│   │-- /middleware  (Auth & error handling)  
│   │-- .env  (Environment Variables)  
│   │-- package.json  
│-- README.md  

```
## 🔧 Setup & Installation
```
# Clone the repository  
git clone https://github.com/yourusername/ecommerce-project.git  
cd ecommerce-project  
```
```
# Install dependencies  
cd client && npm install  
cd ../server && npm install  
```
```
# Setup environment variables  
# Create a .env file in the server folder  
# Add the following variables:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```
```aiignore
Or just add your MongoDB clusterURL in their 
│-- /server
│   │-- /server.js  

mongoose.connect("db_url")
  
```
```
# Run the development server  
cd server && npm start  
cd client && npm start  

# Open in browser  
http://localhost:3000
```


**This project is open-source. Feel free to modify and improve it!**









