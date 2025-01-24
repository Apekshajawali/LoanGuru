
# 🏦 LoanGuru - Credit Assessment & Loan Recommendation Platform

Welcome to **LoanGuru**, your personal loan assistant!  
LoanGuru helps you assess your creditworthiness and recommends the best loan offers across multiple banks, saving you time and effort.

---

## 🎯 Main Benefits
- **Save Time**: No more visiting multiple banks.
- **Better Decisions**: Understand your chances before applying.
- **Best Deals**: Compare offers from many banks in one place.
- **Easy to Use**: Upload documents seamlessly and get instant results.
- **Transparent**: Clear explanation of your credit score.

---

## 📊 Core Features

### Credit Assessment Engine
- Dynamic CIBIL score calculation using:
  - New credit impact (15%)
  - Payment history analysis (35%)
  - Credit utilization metrics (30%)
  - Credit duration assessment (15%)
  - Portfolio diversity evaluation (5%)

### Loan Offer System
- **Dynamic Loan Generation**: See real-time loan offers tailored for you.
- **Multi-Bank Integration**: Compare multiple banks on one platform.
- **Automated Eligibility Check**: Know instantly if you qualify.

### User Management
- Secure **Authentication** with JWT.
- Manage your financial profile with an **Interactive Dashboard**.
- Upload and process documents with ease.

---

## 🖥️ Technical Architecture

### Technology Stack
#### Backend:
- **Node.js** with **Express.js**
- **MongoDB** with **Mongoose ODM**
- **Multer** for document handling

#### Frontend:
- **React.js** with **Tailwind CSS**
- **Axios** for API requests
- **React Router** for navigation

#### Authentication:
- **JWT** for tokens
- **Bcrypt** for password encryption

---

## 🚀 How to Run

### Prerequisites
- **Node.js** (v14+), **npm** (v6+), **MongoDB** (v4.4+)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Apekshajawali/loanguru.git
   cd loanguru
   ```

2. Install dependencies:
   ```bash
   # Server dependencies
   npm install

   # Client dependencies
   cd client
   npm install
   ```

3. Configure environment variables:
   ```bash
   # .env file (server)
   NODE_ENV=development
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/bank
   JWT_SECRET=your_jwt_secret
   JWT_EXPIRE=24h

   # .env file (client)
   REACT_APP_API_URL=http://localhost:3000/api
   ```

4. Set up the database:
   ```bash
   sudo systemctl start mongod
   mongosh
   use bank
   ```

5. Start the app:
   ```bash
   # Development mode
   npm run dev

   # Production mode
   npm run build
   npm start
   ```


---

## 📁 Project Structure
<details>
<summary>Click to expand</summary>

```plaintext
loanguru/
├── client/
│   ├── public/
│   │   └── index.html
│   └── src/
│       ├── components/
│       ├── contexts/
│       ├── hooks/
│       ├── services/
│       ├── utils/
│       ├── App.js
│       └── index.js
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── server.js
├── tests/
├── .gitignore
├── package.json
└── README.md
```
</details>

---

## 👨‍💻 Development Team
- [Apeksha Jawali](https://github.com/Apekshajawali) 
- [Gyanada](https://github.com/Gyan0706)  
- [Aditya Singh](https://github.com/AKdevi99)   
- [Aiman Sabah](https://github.com/Shaiman-N)

---

## 📜 License
This project is licensed under the MIT License. See [LICENSE.md](LICENSE.md) for details.

---

<div align="center">
  © 2024 LoanGuru. All Rights Reserved.
</div>
```


