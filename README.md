# 🛒 Ecommerce Follow Along

## 🚀 E-Commerce Project - Key Takeaways

### 🎯 Project Goals
✅ Build a full-fledged e-commerce app using the MERN stack.  
✅ Gain hands-on experience in real-world full-stack development.  

---

## 📚 Learning Outcomes
📌 Understand the structure of a MERN stack project.  
📌 Set up project repositories and foundational tools.  
📌 Master core functionalities:
- 🔑 User Authentication (Login/Register).  
- 📦 Product & Order Management.  
- 🗃️ Database Schema Design.  

---

## 🛠️ Core Concepts
- 🔹 **REST API Design** → Create endpoints for users, products & orders.  
- 🔹 **MongoDB Schema** → Structure meaningful data models.  
- 🔹 **Authentication** → Secure login & registration systems.  
- 🔹 **Backend Development** → Use Node.js + Express for APIs.  

---

## 🏆 Milestones Overview

### 📌 Project Overview
🚀 Introduction to MERN stack.  
🔍 Live Demo of the final app.  
📌 Set up GitHub repo + README 📜.  

---

## 🛠️ Development Environment Setup
✅ Install tools: **Node.js, npm, MongoDB, VS Code**.  
✅ Initialize the project:
```sh
npm init
```
✅ Install dependencies:
```sh
npm install express mongoose dotenv
```

---

## ⚙️ Backend Development
🛠️ Create REST APIs for:
- 👤 **User Authentication** (Register/Login).  
- 🛍️ **Product Management** (CRUD operations).  
- 📦 **Order Handling** (Orders & Transactions).  

📌 **Database Design:**
- 🏛️ **MongoDB Schemas** for Users, Products, Orders.  
- 🛡️ Implement **middleware** for validation & error handling.  

---

## 🎨 Frontend Development
🖥️ Set up **React project** with `create-react-app` or `Vite`.  
🎨 Build **key UI components**:
- 🔑 **User Pages** (Login, Register, Profile).  
- 🛒 **Product Pages** (Listings, Search, Details).  
- 🛍️ **Order Pages** (Cart, Checkout, History).  
🔀 Use **React Router** for navigation.  
📦 Manage **state** with Redux or Context API.  

---

## 🔗 Integration, Testing & Deployment
🔗 Integrate **Frontend & Backend** using API calls.  
🛠️ Test with **Postman** and fix bugs 🐞.  
🚀 **Deploy** the project:
- 🔥 **Backend** → Heroku, Render, or AWS.  
- 🌐 **Frontend** → Netlify or Vercel.  
🛡️ Ensure **security & performance** before launch!  

---

## 🎯 Final Deliverable
✅ A **fully functional MERN-based** e-commerce app featuring:
- 🔒 **Secure Authentication**.  
- 📦 **Product & Order Management**.  
- 📱 **Responsive & User-Friendly UI**.  
✅ Fully **tested** & **deployed online**! 🚀  

---

🔥 **Let’s build something awesome together!** 💻⚡  

# Milestone 2: Project Structure & Login Page 🚀  

## Overview  
In Milestone 2, we focused on structuring the project, setting up both the frontend and backend, and developing the Login Page for the e-commerce application.  

## Key Accomplishments  

### 📁 Project Structure  
- Organized the project with separate frontend/ and backend/ directories.  

### 🌐 Frontend Setup  
- Initialized a React app for building the user interface.  
- Configured *Tailwind CSS* for utility-based styling.  
- Implemented a fully functional and styled *Login Page*.  

### 🛠 Backend Setup  
- Set up a basic *Node.js + Express* server to prepare for future API integration.  

### 🎯 Learning Outcomes  
By completing this milestone, we learned:  
- How to structure a full-stack project.  
- Setting up a React application with Tailwind CSS.  
- Configuring a Node.js backend.  
- Creating a login page with basic styling and functionality.  

## ✅ Submission Details  
- Code is pushed to the *GitHub repository* created in Milestone 1.  
- The repository includes:  
  - *Proper folder structure* (frontend & backend).  
  - *Functional Login Page*.  
  - *Updated README* summarizing the progress.  

🚀 Ready for the next milestone


# Milestone 3: Project Setup for Backend

In this milestone, we successfully set up the backend for our Ecommerce project using Node.js, Express.js, and MongoDB.

✅ Achievements in this Milestone
Set up a Node.js backend server using Express.
Configured the server to listen on a designated port.
Integrated MongoDB for efficient data storage.
Established a connection between the server and MongoDB to confirm successful integration.


# Milestone 4: Creating User Model and Controller

### Achievements
1. **User Model:**
   - Created a User schema using **Mongoose**.
   - Defined fields such as `name`, `email`, `password`, and `profileImage`.
   - Implemented password hashing using **bcryptjs** for security.

2. **User Controller:**
   - Developed controller functions for user-related actions:
     - Registering a new user.
     - Retrieving user information.
     - Handling user authentication.
   - Integrated the controller with **Express routes**.

3. **Multer Integration:**
   - Configured **Multer** for handling file uploads.
   - Allowed users to upload profile images and store them in a designated folder.


# Milestone 5: Frontend Development - Sign-Up Page

### Overview  
In this milestone, I built the **Sign-Up Page** using **HTML** and **CSS** and added **form validation** to ensure users input valid data.  

### Features  
- **Sign-Up Page**: Created a responsive and user-friendly sign-up form.  
- **Form Validation**: Added validation for required fields, email format, password matching, and minimum password length.  

# Milestone 6 - User Authentication & Encryption

In this milestone, I implemented user authentication with password encryption and saved complete user data in the database.

## Features Implemented

### 1. Encrypt the Password
- Used `bcrypt` to hash the user's password during the signup process.
- Ensured that the hashed password is saved in the database instead of storing the plain text password.

### 2. Store Complete User Data
- Saved all the user's data (e.g., name, email, etc.) into the database.
- Ensured that the password is stored securely and not in plain text.

## How It Works

- During the signup process, the user's password is hashed using `bcrypt`.
- The hashed password is then stored in the database along with other user details like name and email.
- When the user logs in, the password provided is compared with the hashed password in the database for authentication.

This ensures that sensitive user data, especially the password, is stored securely.

---

# Milestone 7 - Login Endpoint

## Overview
This milestone involves creating a login endpoint that allows users to authenticate using their email/username and password.

## Steps

### 1. Create Login Endpoint
- Accept user credentials (email/username and password).
- Retrieve the corresponding user from the database.

### 2. Validate Password
- Use bcrypt to hash the entered password.
- Compare it with the stored hashed password for authentication.

---

## Milestone 8: Product Card Component and Homepage Layout 🚀

### ✅ Frontend Product Card Component
- Designed and implemented a reusable Product Card component.
- Created a responsive homepage to display multiple Product Cards.

---

milestone-9
# Milestone 9: Product Form Creation

## Learning Goals
- Create a form to take product details.
- Allow multiple image uploads.

## Steps
1. Build a product form with necessary fields.
2. Add validation and improve UI/UX.

## Submission
- Push code to GitHub.
- Ensure repository is public.
- Update README with Milestone 9 summary.
- Share repository link in the submission section.

milestone-10
---
# Milestone 10: Mongoose Schema & Endpoint Creation
---
## Learning Goals
- Write a Mongoose schema for products.
- Create an endpoint to validate and store product details in MongoDB.

## Steps
1. Define the product schema with fields like name, description, price, and image URL.
2. Ensure proper validation for each field (e.g., required fields, correct data types).
3. Build a POST endpoint to receive product data.
4. Validate and save product details to MongoDB.

---
# Milestone 11 - Display Products Dynamically
---

## Overview  
In this milestone, we are making our **home page dynamic** by fetching and displaying product data from MongoDB. We will:  
- Create an **API endpoint** in Express to fetch all products.  
- Fetch the data in the **frontend**.  
- Display the products dynamically using the **Product Card** component.  

## Learning Objectives 🎯  
By completing this milestone, you will learn:  
✅ How to write an endpoint to fetch data from MongoDB.  
✅ How to receive and use the data in the frontend.  
✅ How to dynamically display the data using React components.  

## Steps to Follow 📝  
1️⃣ **Backend**: Create an API endpoint to send all product data.  
2️⃣ **Frontend**: Write a function to fetch the product data.  
3️⃣ **UI Update**: Pass the data to the Product Card component and display it dynamically.  

---
# Milestone 12 - My Products Page
---

## Overview  
In this milestone, we will create the **My Products** page that displays all the products added by the logged-in user. We will:  
- Create an **API endpoint** in Express to fetch products based on the user's email.  
- Fetch the data in the **frontend**.  
- Display the filtered products dynamically using the **Product Card** component.  

## Learning Objectives 🎯  
By completing this milestone, you will learn:  
✅ How to write an endpoint to fetch data filtered by the user's email.  
✅ How to receive and use the data in the frontend.  
✅ How to dynamically display the filtered data using React components.  

## Steps to Follow 📝  
1️⃣ **Backend**: Create an API endpoint that filters and sends products based on the user's email.  
2️⃣ **Frontend**: Write a function to fetch the filtered product data.  
3️⃣ **UI Update**: Pass the filtered data to the Product Card component and display it dynamically.  

---
# Milestone 13 - Edit Product Feature
---

## Overview
This milestone adds the functionality to edit uploaded products. The update includes:
- An **Edit** button for each product.
- An endpoint to update existing product details in MongoDB.
- Auto-filling the form with previous data for editing.

## Implementation Steps
1. Created an **API endpoint** to update product details in MongoDB.
2. Added an **Edit** button to the product card.
3. Implemented **auto-fill** functionality in the edit form.
4. Allowed users to modify product details and save changes.

---
# **Product Deletion API - Milestone 14** 🚀  
---

## **Overview**  
This project implements a DELETE endpoint to remove a product from MongoDB using its ID. Additionally, a **Delete button** is added to the frontend, allowing users to delete a product by sending its ID to the backend.  

## **Features**  
✅ API endpoint to delete a product by ID  
✅ Frontend button to trigger the delete request  
✅ MongoDB integration for data persistence  

---
# Milestone 15 - Navbar Component  
---

## Overview  
In this milestone, I created a reusable **Navbar** component for the application. The Navbar includes links to the following pages:  

- Home  
- My Products  
- Add Product  
- Cart  

The Navbar is **responsive** and is included on all pages to enable smooth navigation.  

## Technologies Used  
- React  
- Vite  
- React Router  

## How to Run  
1. Clone the repository  
2. Install dependencies: `npm install`  
3. Start the app: `npm run dev`  

## Submission  
This milestone demonstrates the ability to create reusable components and implement navigation across multiple pages.  
