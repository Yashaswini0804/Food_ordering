# Food Ordering App

A full-stack food ordering application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This app allows users to browse restaurants, view menus, add items to cart, place orders, and manage payments. It also includes an admin panel for managing restaurants, food items, orders, and payments.

## Features

- **User Authentication**: Register and login functionality
- **Restaurant Management**: Browse and search restaurants
- **Menu Display**: View food items with prices and descriptions
- **Shopping Cart**: Add, remove, and update cart items
- **Order Placement**: Place orders with payment integration
- **Order Tracking**: View order history and status
- **Admin Panel**: Manage restaurants, food items, orders, and payments
- **Responsive Design**: Works on desktop and mobile devices

## Tech Stack

- **Frontend**: React.js, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Integration**: Stripe or similar payment gateway

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/Yashaswini0804/food-ordering.git
   cd food-ordering
   ```

2. Install server dependencies:
   ```
   npm install
   ```

3. Install client dependencies:
   ```
   cd client
   npm install
   cd ..
   ```

4. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add your MongoDB connection string, JWT secret, and other required variables

5. Start the development server:
   ```
   npm run dev
   ```

6. Open your browser and navigate to `http://localhost:3000`

## Usage

- Register a new account or login with existing credentials
- Browse restaurants and their menus
- Add items to your cart
- Proceed to checkout and complete payment
- Track your orders in the profile section
- Admin users can access the admin panel to manage the app

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.
