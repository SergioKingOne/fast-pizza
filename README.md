# 1. Introduction

# Purpose and Overview
The "Fast Pizza" web app is a user-friendly platform for ordering pizzas quickly and conveniently. Users can browse a dynamic pizza menu, customize their orders, and request priority delivery. This documentation provides an in-depth guide to the app's features and functionalities.

# Target Audience
- Pizza enthusiasts
- Individuals looking for a quick and easy pizza ordering experience

# Project Scope
The scope of the project includes:

- A simple web app with a responsive UI
- Dynamic loading of the pizza menu from an external API
- User input for name, phone number, and address
- GPS location integration for delivery
- Adding pizzas to a cart
- Marking orders as "priority"
- Order submission with unique alphanumeric IDs
- Order lookup
- Temporary storage of user data

# Design Palette
The app's design palette includes the following colors from the Tailwind CSS palette:

- Yellow
- White
- Black
- Red
- Green


# 2. System Architecture
# High-Level Architecture
The "Fast Pizza" web app follows a client-server architecture:

- Frontend: Developed using React, Tailwind CSS, and Vite.
- Backend: No backend or database; data is managed in the frontend.
- Third-party API integration: BigDataCloud for GPS location.

# Components and Modules
- React Components: Organized into reusable components for UI elements, forms, and pizza items.
- Redux Store: Manages the app's state, including cart items and priority order status.
- React-Router: Handles navigation within the app.
- Third-Party API Module: Connects to the BigDataCloud API for GPS location.

# 3. Technologies Used
# Frontend Technologies
- React
- Tailwind CSS
- Vite
- React-Router
- Redux

# Third-Party APIs
- BigDataCloud (For GPS location)

# 4. User Flows
# User Journey
1. Users enter the app.
2. Browse the dynamic pizza menu.
3. Customize orders, specify name, phone number, and address.
4. Add pizzas to the cart.
5. Mark orders as "priority."
6. Submit orders and receive unique order IDs.
7. Optionally, look up previous orders using the order ID.

# Ordering Process
- Users can select pizzas from the menu, specify quantity, and customize toppings.
- Name, phone number, and address are provided during the order process.
- Users can mark orders as "priority" before submission.

# Priority Order Workflow
Users can checkmark the "priority" option during the order process.
Alternatively, they can set an order as "priority" even after completing the order.

# 5. Features and Functionality
## Pizza Menu Loading (External API)
- The pizza menu is dynamically loaded from an external API.

# User Input (Name, Phone Number, Address)
- Users provide their name, phone number, and delivery address.

# GPS Location Integration (BigDataCloud)
- The BigDataCloud API is used to obtain GPS coordinates based on user input.

# Adding Pizzas to Cart
- Users can add multiple pizzas to the cart before placing an order.

# Marking Orders as Priority
- Users can mark orders as "priority" during the order process or afterward.

# Order Submission
- Orders are submitted via a POST request to the API, including user data and selected pizzas.

# Unique Order ID Generation (Alphanumeric)
- Unique order IDs are generated in alphanumeric format.

# Order Lookup
- Users can retrieve order details based on their unique order ID.
