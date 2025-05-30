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

# Milestone 26: Get User Orders Endpoint

## 📄 Overview
In Milestone 26, we implemented a backend endpoint to retrieve all orders of a specific user. This endpoint receives the user's email, retrieves the user's `_id` based on the provided email, and returns all orders associated with that user.

## 🛠️ Key Accomplishments

### 🔗 API Endpoint
- Created a **GET** endpoint at `/api/get-orders`.
- Received the user's email as a parameter.
- Retrieved the user's `_id` based on the provided email.

### 📚 Order Retrieval
- Fetched all orders associated with the user's `_id`.
- Sent the retrieved orders in the API response.

### 🔒 Data Integrity
- Ensured data consistency and validation while retrieving orders.

## 💡 Learning Outcomes
- Developed backend API to retrieve user-specific orders.
- Strengthened understanding of MongoDB queries and schema management.
- Enhanced skills in API endpoint implementation and validation.

## ✅ Submission Details
Code is pushed to the GitHub repository created in earlier milestones.

### The repository includes:
- Updated backend endpoint for retrieving user orders.
- Corrected and optimized API logic.
- Updated README to reflect milestone progress.

# Milestone 27: My Orders Page Implementation

## 📄 Overview
In Milestone 27, we implemented a frontend page to display all the user's orders. The page sends a GET request to the `/api/get-orders` endpoint created in the previous milestone and retrieves the orders associated with the user's email.

## 🛠️ Key Accomplishments

### 🎨 Frontend Page
- Created a **My Orders** page to display all user orders.
- Sent a **GET** request to the `/api/get-orders` endpoint with the user's email.
- Fetched and displayed all orders in a user-friendly format.

### 🧭 Navigation Enhancement
- Added **My Orders** link in the navbar for easier navigation.

### 📚 Data Display
- Ensured that the order details are displayed properly with necessary information such as product name, quantity, price, and status.

## 💡 Learning Outcomes
- Developed a frontend page to retrieve and display user orders.
- Strengthened understanding of API consumption and dynamic rendering in React.
- Enhanced navigation by adding relevant links to the navbar.

## ✅ Submission Details
Code is pushed to the GitHub repository created in earlier milestones.

### The repository includes:
- Fully functional **My Orders** page.
- Corrected and optimized frontend logic.
- Updated README to reflect milestone progress.

# Milestone 28: Cancel Order Feature

## 📄 Overview
In Milestone 28, we implemented a cancel button in the **My Orders** page and created a backend endpoint to cancel an order. Users can now cancel placed orders, and the order status will be updated accordingly.

## 🛠️ Key Accomplishments

### 🎨 Frontend Enhancements
- Added a **Cancel Order** button for each order on the **My Orders** page.
- Ensured that the button is not displayed if the order is already canceled.

### 🔗 API Endpoint
- Created a **POST** endpoint at `/api/cancel-order`.
- Received the `orderId` as a parameter.
- Retrieved the order using `orderId` and updated the status to **canceled**.
- Saved the updated order in the database.

### 🧾 Order Status Management
- Ensured that canceled orders cannot be canceled again.
- Properly handled order status updates and data consistency.

## 💡 Learning Outcomes
- Implemented order cancellation functionality in the frontend and backend.
- Strengthened understanding of MongoDB queries and update operations.
- Enhanced API development and frontend integration.

## ✅ Submission Details
Code is pushed to the GitHub repository created in earlier milestones.

### The repository includes:
- Fully functional **Cancel Order** feature.
- Corrected and optimized API logic.
- Updated README to reflect milestone progress.

# Milestone 29: PayPal Integration Preparation

## 📄 Overview
In Milestone 29, we prepared the application for integrating an online payment gateway using the **PayPal API**. We added options for **Cash on Delivery (COD)** and **Online Payment** on the order confirmation page.

## 🛠️ Key Accomplishments

### 💳 Payment Options
- Added **radio buttons** to select between COD and Online Payment.
- Displayed **PayPal Buttons** dynamically when Online Payment is selected.

### 🔐 PayPal Sandbox Setup
- Created a **PayPal Developer Account**.
- Generated and saved the **Sandbox Account User ID**.
- Copied and stored the **Client ID** from the PayPal Sandbox account.

### 📚 Payment Flow Implementation
- Prepared frontend to dynamically render PayPal buttons.
- Configured initial structure for integrating PayPal API in the next milestone.

## 💡 Learning Outcomes
- Learned how to set up a PayPal sandbox account.
- Understood how to add payment options and dynamically display PayPal buttons.
- Strengthened knowledge on integrating online payment gateways.

## ✅ Submission Details
Code is pushed to the GitHub repository created in earlier milestones.

### The repository includes:
- Updated order confirmation page with payment options.
- Initial setup for PayPal integration.
- Updated README to reflect milestone progress.


# Milestone 30: PayPal API Integration

## 📄 Overview
In Milestone 30, we successfully implemented the PayPal API to enable online payments in our application. Building upon the previous milestone, we used the client key from our PayPal sandbox account to integrate the payment system.

## 🛠️ Key Accomplishments

### 💳 PayPal API Integration
- Installed the `react-paypal-js` NPM package to facilitate integration.
- Used the **PayPalScriptProvider** component to display online payment options.
- Implemented dynamic rendering of PayPal buttons for payment processing.

### 🔗 Payment Flow Implementation
- Utilized the client key generated in the PayPal sandbox account.
- Configured payment options to include credit, debit, and PayPal payments.

### 📚 Enhanced Order Flow
- Successfully integrated PayPal payments into the order confirmation page.
- Ensured seamless transition between COD and PayPal payment methods.

## 💡 Learning Outcomes
- Gained hands-on experience with PayPal API integration.
- Learned how to use `react-paypal-js` to manage PayPal scripts and buttons.
- Strengthened understanding of secure payment handling and dynamic UI integration.

## ✅ Submission Details
Code is pushed to the GitHub repository created in earlier milestones.

### The repository includes:
- Fully functional PayPal payment integration.
- Corrected and optimized API logic.
- Updated README to reflect milestone progress.

# 🧠 Milestone 31 - Global State Management using Redux

Welcome, Kalvians! 🎉  
This milestone focuses on implementing **global state management** using **Redux** in a React application.

---

## 🚀 Learning Goals

By the end of this milestone, I learned:

- How to use **Redux** for managing global state.
- How to configure a **Redux store**.
- How to create actions and reducers.
- How to integrate Redux with a React application using the `Provider` component from `react-redux`.

---

## 💠 Steps Followed

1. ✅ Installed `react-redux` via npm:
   ```bash
   npm install react-redux
   ```

2. ✅ Created a new folder named `store/` with the following files:
   - `store.js`: Configured Redux store and reducer.
   - `userActions.js`: Defined the `setEmail` action.

3. ✅ Implemented a global email state:
   - Created a `userReducer` function to manage email.
   - Configured the store using `configureStore()` from Redux Toolkit (or `createStore()` from Redux).

4. ✅ Wrapped the `<App />` component inside a Redux `<Provider>` in `index.js`, passing the store as a prop.

5. ✅ Prepared for the next lesson to use the email across all files via Redux.

---
## 🚀 Milestone 32 - Global State Management with Redux

In this milestone, we focused on improving state management across our Ecommerce Follow-Along project by using **Redux** to store and access user data globally across multiple pages.

### 🎯 What Was Achieved:

- Implemented **Redux** to handle the global state.
- Stored the **user's email** in the Redux store upon login using the `dispatch` method.
- Accessed the stored **email** in all other pages using the `useSelector` hook.
- Ensured consistent and centralized user data access across components, improving app reliability and reducing prop-drilling.
  
### 🛠 Tech Used:

- React.js
- Redux Toolkit
- React-Redux

### 📂 Files Modified:

- `Login.jsx`: Used `dispatch` to save email in global state.
- `store.js` / `userSlice.js`: Created Redux slice for managing user state.
- Other pages (e.g. Dashboard, Profile, etc.): Used `useSelector` to access the email from the store.

---

### ✅ How to Run:

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/Ecommerce-Follow-Along.git
   cd Ecommerce-Follow-Along
Install dependencies:

bash
Copy
Edit
npm install
Start the development server:

bash
Copy
Edit
npm start
💡 Summary:
This milestone helped in understanding the power of Redux for managing global application state efficiently. It was a crucial step in making the app scalable and maintainable as more user-specific features are added.

kotlin
Copy
Edit

Let me know your GitHub repo name and I can customize this further for you!






You said:
Logo
Livebooks
Backend Web Development [V2]
Saving password and setting username in cookie[v2]
Follow-along project milestone #33
Hey Kalvians!

Welcome to Milestone 33! 🌟

Today, we will learn how to create an JWT token and store them inside an cookie.

Learning Goals 🎯
By the end of this milestone, you will:

Learn how to create an JWT token.
How to store the tokens inside the cookie.
Steps for Milestone 33📝
Download jsonwebtoken package using NPM
Use sign method to create an JWT token with mail and ID
Give maxAge to set expire time
Add the cookie inside the response that helps you to store the cookie inside browser.
This lesson will help you in understanding how to create an JWT token and store it inside an token.

Submission Guidelines 📥

Push your code to your GitHub repository.
Ensure your repository is publicly accessible.
Update the README file to summarize your progress for Milestone 33.
Share the repository link in the assignment submission section.
Good luck, Kalvians! ✨

Take this assignment to show your understanding of the topics you have learned.

Max. Duration:
1 hr
How did you like this assignment?

Not Good

Okayish

Good

Very Good

Previous

Follow-along project milestone #32
Next

Assignment | ASAP Project - working with cookie

send me readme file


ChatGPT said:
Here's a sample README.md section for Milestone 33 that you can add to your GitHub repo:

markdown
Copy
Edit
## 🔐 Milestone 33 - JWT Token Creation & Cookie Storage

In this milestone, we implemented **JWT authentication** by generating a token upon login and securely storing it inside a browser cookie. This helps in maintaining persistent user sessions.

### 🎯 What Was Achieved:

- Installed the `jsonwebtoken` package using NPM.
- Created a **JWT token** using the `sign()` method with user's **email** and **ID**.
- Set an **expiry time** for the token using the `maxAge` option.
- Sent the token to the frontend by attaching it as a **cookie** in the server response.

### 🛠 Tech Used:

- Node.js
- Express.js
- jsonwebtoken
- cookie-parser

### 📂 Key Implementation Files:

- `authController.js` or similar:
  - Used `jwt.sign()` to generate token:
    ```js
    const token = jwt.sign({ id: user._id, email: user.email }, 'yourSecretKey', {
      expiresIn: '1d'
    });
    ```
  - Set cookie in response:
    ```js
    res.cookie('jwt', token, {
      httpOnly: true,
      maxAge: 24 * 60 * 60 * 1000 // 1 day
    });
    ```

- `server.js` or `app.js`:
  - Imported and used `cookie-parser` middleware:
    ```js
    const cookieParser = require('cookie-parser');
    app.use(cookieParser());
    ```

---
