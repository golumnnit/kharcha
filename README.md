Kharcha Expense Tracker

Kharcha is a comprehensive expense tracking mobile application designed to help users manage and categorize their monthly expenses effortlessly. It fetches data from various UPI apps like Google Pay, PhonePe, and other bank transactions to provide a clear and organized overview of spending. The app categorizes expenses into groceries, travel, food/restaurants, rent, electricity bills, and miscellaneous expenses. Users can set budgets, receive spending alerts, and generate detailed reports to better understand and control their finances.

Features

Automatic Expense Tracking:

UPI Integration: Seamless integration with popular UPI apps (Google Pay, PhonePe, Paytm, etc.) to automatically fetch and categorize transactions.
Bank Sync: Connect with bank accounts to pull transaction data for comprehensive tracking.
Expense Categorization:

Auto Categorization: Intelligent algorithms to auto-categorize expenses into predefined categories (groceries, travel, food/restaurants, rent, electricity, miscellaneous).
Manual Adjustment: Allow users to manually re-categorize transactions if needed.
Budgeting:

Set Budgets: Users can set monthly budgets for different categories.
Spending Alerts: Notifications for when spending nears or exceeds set budgets.
Reports and Analytics:

Monthly Reports: Generate monthly spending reports with breakdowns by category.
Trends and Insights: Visualize spending trends over time and get insights on spending habits.
User Interface:

Dashboard: An overview of the month’s expenses, budget status, and alerts.
Category View: Detailed view of expenses within each category.
Transaction List: Comprehensive list of all transactions with filtering and search options.
Security and Privacy:

Data Encryption: All financial data is encrypted to ensure privacy and security.
Secure Authentication: Multi-factor authentication to protect user accounts.
Tech Stack

Backend

1. Node.js
2. Express.js
3. MongoDB
4. JWT for authentication

Frontend

1. React Native
2. Context API for state management

Installation

Prerequisites
1. Node.js and npm installed
2. MongoDB installed and running
3. React Native development environment setup

Clone the Repository

git clone https://github.com/golumnnit/kharcha.git

cd kharcha

Backend Setup
1. Navigate to the backend directory:
cd backend

2. Install dependencies:
npm install

3. Create a .env file in the backend directory and add your MongoDB connection string and JWT secret key:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

4. Start the backend server:
npm start

Frontend Setup
1. Navigate to the frontend directory:
cd ../frontend

2. Install dependencies:
npm install

3. Start the frontend app:
npm start

Usage
1. Open the app in your browser or mobile emulator.
2. Sign up or log in to create an account.
3. Link your UPI apps and bank accounts to automatically fetch transactions.
4. View your expenses in different categories on the dashboard.
5. Set budgets for each category and receive spending alerts.
6. Generate and view monthly reports to analyze your spending habits.

Contributing
1. Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
1. Create a new branch (git checkout -b feature/your-feature).
2. Make your changes and commit them (git commit -m 'Add some feature').
3. Push to the branch (git push origin feature/your-feature).
4. Open a pull request.
