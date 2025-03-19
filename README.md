# ecomm-deploy
Deployed-Live:https://ecomm-deploy.onrender.com/


## Overview
**ecomm-deploy** is a full-stack eCommerce website built using the **MERN** stack (MongoDB, Express.js, React.js, and Node.js). This project includes authentication, product management, and a cart system. The payment integration is currently pending.

## Features
- **User Authentication**: Sign up, login, and logout functionality.
- **Product Management**: Add, update, and delete products.
- **Shopping Cart**: Add items to the cart and manage quantities.
- **Order Processing**: Users can place orders and track them.
- **Middleware Implementation**: Secure API routes.
- **Database Integration**: MongoDB for data storage.

## Installation
### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB

### Steps to Run
1. **Clone the Repository**
   ```sh
   git clone https://github.com/GuraaseesSingh/ecomm-deploy.git
   cd ecomm-deploy
   ```

2. **Install Dependencies**
   ```sh
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env` file in the root directory and add:
   ```
   MONGO_URI=<your_mongodb_connection_string>
   JWT_SECRET=<your_jwt_secret> 
   ```

4. **Run the Server**
   ```sh
   npm start
   ```

5. **Run the Frontend** (If applicable)
   ```sh
   cd client
   npm start
   ```

## Folder Structure
```
.
├── models        # Database schemas
├── routes        # API routes
├── middleware    # Middleware functions
├── views         # Frontend templates (if using server-side rendering)
├── public        # Static files
├── app.js        # Main application entry point
├── package.json  # Dependencies and scripts
└── README.md     # Project documentation
```

## Future Enhancements
- **Payment Integration** (e.g., Stripe, Razorpay)
- **Admin Dashboard**
- **Wishlist Feature**
- **Enhanced UI/UX**

## Contributing
Feel free to submit issues or contribute to the project. Fork the repository and create a pull request.

## License
This project is licensed under the MIT License.

---
### Author: Guraasees Singh

