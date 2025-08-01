
# 💰 MoneyWise Frontend

This is the frontend for the **MoneyWise** budget management application. It is built using **HTML**, **CSS**, and **vanilla JavaScript** to provide a user-friendly interface for tracking expenses and deposits.

## 📁 Folder Structure

```
moneywise-frontend/
│
├── index.html              # Login page
├── sign-up.html            # Signup page
├── user-home.html          # User dashboard
├── admin-dashboard.html    # Admin dashboard
├── style.css               # General styling
├── script.js               # Main JS logic
├── user-home.js            # Logic for user dashboard
├── admin-login.js          # Admin login logic
├── history.js              # For showing transaction history
├── images/                 # Contains UI images
```

## 🚀 Features

- User and Admin login/signup
- Role-based dashboard views
- Add/view expenses and deposits
- View balance updates
- Admin dashboard with charts and user management
- Responsive design

## 📦 Setup

Just open `index.html` in your browser.
Make sure the backend server is running on `http://localhost:5000` (or your configured API URL).

## 📊 Dependencies

- Chart.js (for charts)
- Fetch API (to communicate with backend)
- LocalStorage (for JWT token handling)
