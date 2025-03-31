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

---
# Milestone 16 - Product Info Page  
---

## Overview  
In this milestone, I created a **Product Info Page** that displays detailed product data. The page includes:  
- Product details (name, price, description, etc.)  
- Quantity selection  
- "Add to Cart" button  

## Technologies Used  
- React  
- Vite  
- React Router  

---
# Milestone 17 - Add to Cart Functionality  
---

## Overview  
In this milestone, we implemented an API endpoint to add products to the cart and store them in the database.  

## Features Implemented  
- Updated the **User Schema** to include a cart field.  
- Created a **Cart Schema** to store product details.  
- Developed an **API endpoint** to add products to the cart.  

## Steps Taken  
1. Defined the Mongoose **Cart Schema**.  
2. Modified the **User Schema** to store cart items.  
3. Created an **API route** to receive product details and store them in the database.  

---
# Milestone 18 - Fetch Cart Products  
---

## Overview  
In this milestone, we created a backend endpoint to retrieve all products inside a user's cart for display on the cart page.  

## Features Implemented  
- Developed an **API endpoint** to fetch cart products using the user's email.  
- Retrieved and returned **cart items** from the database.  

## Steps Taken  
1. Created an **endpoint** to receive requests from the cart page.  
2. Queried the database to **fetch all cart items** associated with the user.  
3. Returned the **cart data** in the response.  

---
# Milestone 19 - Cart Functionality  
---

## Overview  
In this milestone, I implemented the cart functionality by:  
- Creating a frontend cart page to display products.  
- Adding + and - buttons to increase/decrease product quantity.  
- Developing backend endpoints to update the quantity dynamically.  

## Features Implemented  
- Display products inside the cart.  
- Update product quantity using buttons.  
- Backend support for modifying cart item quantities.

---
# Milestone 20 - Profile Page Functionality  
---

## Overview  
In this milestone, I implemented the profile page functionality by:  
- Creating a backend endpoint to send user data via email.  
- Developing a frontend profile page to display user details.  
- Displaying profile photo, name, email, and addresses.  

## Features Implemented  
- Fetch and display user profile data.  
- Show profile photo, name, and email in one section.  
- Display addresses in another section with an "Add Address" button.  
- If no address is available, show "No address found" message.

---
# Milestone 21 - Address Form Functionality  
---

## Overview  
In this milestone, I implemented the address form functionality by:  
- Creating a frontend form for address input.  
- Capturing user details like country, city, address1, address2, zip code, and address type.  
- Navigating to the form page when the "Add Address" button is clicked in the profile page.  

## Features Implemented  
- Created an address form page.  
- Stored input address using state management.  
- Integrated navigation from the profile page to the address form.

---
# Milestone 22 - Address Storage Functionality  
---

## Overview  
In this milestone, I implemented the backend functionality to store user addresses by:  
- Creating an endpoint to receive address data from the frontend form.  
- Storing the received address inside the user profile in the database.  
- Managing the address array within the user collection.  

## Features Implemented  
- Developed a backend endpoint to handle address storage.  
- Integrated the endpoint with the address form.  
- Ensured addresses are added to the user collection in the database.

---
# Milestone 23 - Place Order Functionality  
---

## Overview  
In this milestone, I implemented the place order functionality by:  
- Adding a "Place Order" button inside the cart page.  
- Creating a select address page to display all available addresses and allow selection of a delivery address.  
- Writing a Mongoose schema for storing order details.  
- Developing a backend endpoint to retrieve all user addresses.  

## Features Implemented  
- Added a "Place Order" button that navigates to the select address page.  
- Displayed available addresses with a selection option.  
- Created a backend schema for order storage.  
- Built an endpoint to send user addresses to the frontend.

---
# Milestone 24 - Order Confirmation Page  
---

## Overview  
In this milestone, I implemented the order confirmation functionality by:  
- Creating an order confirmation page in the frontend.  
- Displaying the products being ordered.  
- Showing the selected delivery address.  
- Displaying the total cart value.  
- Adding a "Place Order" button at the bottom.  

## Features Implemented  
- Order confirmation page with product details.  
- Display of selected delivery address.  
- Calculation and display of total cart price.  
- Final "Place Order" button for order submission.

# Milestone 25: Placing Order Endpoint

## 📄 Overview
In Milestone 25, we implemented the backend endpoint to place orders. This endpoint receives order details, retrieves the user's _id based on the provided email, and stores each order with the same address in the database.

## 🛠️ Key Accomplishments

### 🔗 API Endpoint
- Created a **POST** endpoint at `/api/place-order`.
- Received product, user, and address details.
- Fetched the user's `_id` based on the provided email.

### 🚳 Order Storage
- Stored order details using the **Order** schema.
- Created a new order for each product with the same address.

### 📚 Database Schema
- Updated the **Order** schema to include `product`, `user`, `address`, and `status` fields.
- Ensured data integrity and consistency with proper validation.

## 💡 Learning Outcomes
- Developed backend API for placing orders.
- Retrieved user details using email and stored order data.
- Strengthened understanding of MongoDB schema design and order management.

## ✅ Submission Details
Code is pushed to the GitHub repository created in earlier milestones.

### The repository includes:
- Updated backend endpoint for order placement.
- Corrected and optimized API logic.
- Updated README to reflect milestone progress.