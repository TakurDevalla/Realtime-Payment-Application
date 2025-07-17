# 💸 Real-Time Payment Application

Welcome to the Real-Time Payment Application — a modern, secure, and efficient platform for peer-to-peer financial transactions. This application enables users to register, manage accounts, and perform real-time money transfers with ease.

## 🚀 Features

- Secure **User Authentication & Authorization** using JWT
- Real-time **Account Balance** updates
- **User Search** functionality to find other users
- **Instant Money Transfers** between accounts with confirmation
- MongoDB **transaction support** for data integrity

## 🛠️ Technology Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with ACID-compliant transactions)
- **Authentication**: JWT (JSON Web Tokens)

## ⚙️ Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/your-repo-name.git


2. **Set Environment Variables**: Navigate to the `frontend` and `backend` folders and add necessary environment variables. You may need to create a `.env` file and configure it with required variables:
   In the backend/.env file:

   ```
   MONGO_URL = your-mongo-url
   PORT = 3000
   JWT_SECRET = your-jwt-secret
   ```

   In the frontend/.env file:

   ```
   VITE_SERVER_URL = your-server-url
   ```

3. **Install Dependencies**: Install dependencies in the `frontend` and `backend` folders using npm or yarn:

   ```
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

4. **Start the Backend Server**: In the `backend` folder, start the development server using npm:

   ```
   npm run dev
   ```

5. **Start the Frontend**: In the `frontend` folder, start the frontend application:

   ```
   npm run dev
   ```

🔄 Database Transactions
This application uses MongoDB transactions to ensure atomicity in fund transfers. Every transaction is either fully committed or completely rolled back in case of failure, ensuring financial data integrity.

🤝 Contributions
We welcome contributions! If you find a bug or have a feature suggestion, feel free to open an issue or submit a pull request.

Thank you for using the Real-Time Payment App! 💰
Happy Coding! 🚀
