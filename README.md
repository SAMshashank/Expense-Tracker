# 💸 Expense Tracker Website

An advanced **Expense Tracker Web Application** built with **React (Vite)** for the frontend and **Node.js, Express.js, and MongoDB** for the backend.  
It helps users securely manage their incomes and expenses, visualize financial data, and generate downloadable reports.

# 🧑‍💻 Author

Name: Shashank Kushwaha

GitHub: @SAMshashank
---


## 📌 Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)


## 🚀 Features

- **User Authentication**  
  Secure login and signup system using JWT (JSON Web Tokens).

- **Dashboard Overview**  
  Displays Total Balance, Total Income, and Total Expenses in clean summary cards.

- **Income Management**  
  - Add, view, and delete income sources.
  - Export income data to Excel format.

- **Expense Management**  
  - Add, view, and delete expenses.
  - Categorized expense tracking.
  - Export expense data to Excel format.

- **Interactive Charts**  
  Visualize financial data using:
  - **Bar Charts**
  - **Pie Charts**
  - **Line Charts**

- **Recent Transactions**  
  Quickly access the latest income and expense records.

- **Expense & Income Reports**  
  Easily download all your income and expense data in Excel format.

- **Mobile Responsive UI**  
  Seamlessly accessible on desktops, tablets, and smartphones.

- **Intuitive Navigation**  
  Sidebar navigation menu for Dashboard, Income, Expenses, and Logout options.

- **Easy Deletion Functionality**  
  Hover over income/expense cards to reveal a delete button for quick management.

---

## 🛠️ Tech Stack

**Frontend**
- React.js (with Vite)
- Tailwind CSS
- Axios
- React Router

**Backend**
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- Multer (for profile photo upload)
- ExcelJS (for exporting Excel reports)

---



# Install client dependencies
cd frontend
npm install

# Install server dependencies
cd ../backend
npm install

## Setup .env

PORT=5000
MONGODB_URI=your-mongodb-connection-string
JWT_SECRET=your-secret-key

node -e "console.log(require('crypto').randomBytes(64).toString('hex'))" 


