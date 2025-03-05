# Follow Along E-Commerce Website

## Key Features

### 1. REST API
- Implements RESTful principles for efficient client-server communication.
- Endpoints for managing products, users, and orders.

### 2. MERN Stack
- Built with MongoDB, Express.js, React, and Node.js.
- Ensures scalability, performance, and a seamless full-stack experience.

### 3. Order Handling
- Streamlined order processing from cart to checkout.
- Real-time updates for order status and inventory management.

### 4. Product Listing & Management
- Features for adding, editing, and removing products.
- Search and filter functionality for an optimized user experience.

### 5. User Authentication
- Secure authentication with JWT.
- Role-based access control for users and admins.

---

## Milestone 2: Project Setup 🚀
✅ Structured the project with separate frontend and backend directories.
✅ Initialized a React app for the frontend and a Node.js server for the backend.

## Milestone 3: Backend Setup 🚀
✅ Organized backend code with separate folders for routes, controllers, models, and middleware.
✅ Created a backend server using Node.js and Express.
✅ Integrated MongoDB to store and manage data.
✅ Implemented a global error handler for better debugging.

## Milestone 4: Creating User Model and Controller 🚀
✅ Defined a User Schema using Mongoose.
✅ Integrated bcrypt for secure password hashing.
✅ Developed controller functions for user management.
✅ Configured Multer to handle file uploads (e.g., profile pictures).

## Milestone 5: Creating the Signup Page 🚀
✅ Designed the Sign-Up page using Tailwind CSS.
✅ Implemented client-side form validation.

## Milestone 6: Backend Signup Endpoint and Password Encryption 🚀
✅ Created a new route to handle user registration.
✅ Used bcrypt to hash passwords securely.

## Milestone 7: Backend Login Endpoint and Password Validation 🚀
✅ Created a backend route for user login.
✅ Implemented password validation using bcrypt.compare.

## Milestone 8: Product Card Component and Homepage Layout 🚀
✅ Designed and implemented a reusable Product Card component.
✅ Created a responsive homepage to display multiple Product Cards.

## Milestone 9: Product Input Form 🚀
✅ Designed a form for adding product details.
✅ Integrated backend database storage with validation.

## Milestone 10: Product Schema and API Endpoint 🚀
✅ Defined a Product Schema in Mongoose.
✅ Implemented validation for fields like name, price, and image URL.
✅ Created a POST endpoint to store product details in MongoDB.
✅ Ensured proper validation before saving the data.

## Milestone 11: Dynamic Product Display 🚀
✅ Created an endpoint to retrieve all stored products from MongoDB.
✅ Implemented API call logic in the frontend to fetch data dynamically.
✅ Passed fetched product data to the Product Card component.
✅ Rendered product information dynamically on the homepage.

## Milestone 12: My Products Page 🚀
✅ Created a backend endpoint to retrieve products associated with the logged-in user's email.
✅ Queried the MongoDB database to fetch only those products matching the user's email.
✅ Implemented an API call to request user-specific product data from the backend.
✅ Stored the retrieved data in the application state for dynamic rendering.
✅ Passed the fetched data to the Product Card component.
✅ Rendered the products dynamically on the "My Products" page.

## Milestone 13: Editing Uploaded Products 🚀
✅ Created an endpoint to receive and update product details in MongoDB.
✅ Implemented logic to find the product by its ID and modify the existing data.
✅ Added an Edit button to each product card.
✅ When clicked, it fetches the product details and auto-fills the form.
✅ Allowed users to modify product details directly within the form.
✅ Implemented a Save Changes feature to update product details in the database.

## Milestone 14: Deleting Products 🚀
✅ Created an endpoint to delete a product by its ID from MongoDB.
✅ Implemented logic to find the product and remove it from the database.
✅ Added a Delete button to each product card.
✅ When clicked, it sends the product ID to the server endpoint for deletion.
✅ Ensured the product is removed from the frontend dynamically after successful deletion.
✅ Implemented confirmation prompts before deletion for better user experience.

## Milestone 15: Navbar Component 🚀
✅ Designed a Nav component with links to key pages:
  - Home
  - My Products
  - Add Product
  - Cart
✅ Ensured the Navbar adapts to all screen sizes.
✅ Implemented a mobile-friendly design with a collapsible menu.
✅ Added the Nav component to all application pages.
✅ Ensured smooth and intuitive navigation between different sections.

