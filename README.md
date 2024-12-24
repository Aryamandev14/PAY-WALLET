# Pay-Wallet

## Overview
Pay-Wallet is an end-to-end payment wallet solution built using modern web technologies. It provides users with a secure and seamless experience for managing payments and transactions. The application utilizes a robust backend with JWT authentication and a responsive frontend interface for a smooth user experience.

## Features
- User registration and authentication (JWT-based).
- Secure payment transactions.
- Middleware for request validation and security.
- Responsive UI with Tailwind CSS.
- Backend built with Express.js and Node.js.
- Data storage using MongoDB.
- Error handling and request validation middleware.

## Tech Stack
- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)

## Installation

### Prerequisites
- Node.js installed on your system
- MongoDB instance running locally or on the cloud

### Clone the Repository
```bash
git clone https://github.com/your-username/pay-wallet.git
cd pay-wallet
```

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file and add the following environment variables:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend development server:
   ```bash
   npm start
   ```

## Usage
1. Navigate to `http://localhost:3000` to access the application.
2. Register or log in using your credentials.
3. Perform secure transactions and manage your wallet.

## Project Structure
```
pay-wallet/
├── backend/
│   ├── models/         # MongoDB models
│   ├── routes/         # API routes
│   ├── middleware/     # Request validation and authentication middleware
│   ├── controllers/    # Business logic and request handlers
│   └── server.js       # Entry point for the backend server
├── frontend/
│   ├── src/
│   │   ├── components/ # Reusable React components
│   │   ├── pages/      # Application pages
│   │   ├── utils/      # Helper functions
│   │   └── App.js      # Main React application
├── README.md
└── package.json
```

## API Endpoints
### Authentication
- **POST** `/api/auth/register` - Register a new user
- **POST** `/api/auth/login` - Log in an existing user

### Transactions
- **POST** `/api/transactions` - Create a new transaction
- **GET** `/api/transactions` - Get user transactions

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements
- Built with Express.js, React, and Tailwind CSS.
- Authentication powered by JWT.
- Database operations handled by MongoDB.

---

Happy coding!

