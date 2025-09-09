# Evangadi Forem 🌟

A modern, full-stack **Q&A forum** web application where users can ask questions, provide answers, and engage in discussions — similar to Stack Overflow.  

---

## 🚀 Tech Stack

**Frontend**  
- ⚛️ React  
- 🎨 Bootstrap  
- 🔗 React Router DOM  
- 🔒 @fvilers/disable-react-devtools (security)  

**Backend**  
- 🟢 Node.js  
- 📦 Express.js  
- 🗄️ MySQL  
- 🔐 JWT Authentication  
- 🔑 Bcrypt.js (password hashing)  
- 🆔 UUID (unique identifiers)  
- 🌐 dotenv, cors, nodemon, concurrently  

---

## 📁 Project Structure

```
evangadi-forem/
├── clint/ # Frontend React application
│ ├── src/ # Source files
│ ├── public/ # Static assets
│ └── package.json # Frontend dependencies
│
└── server/ # Backend Node.js application
├── server.js # Entry point
├── controllers/ # Route controllers
├── models/ # Database models
├── routes/ # API routes
├── middleware/ # Custom middleware
├── utils/ # Utility functions
└── package.json # Backend dependencies
```



---

## 💡 Features

- ❓ Users can **ask questions**  
- 💬 Users can **reply to questions**  
- 🔐 **JWT-based authentication** and secure password hashing  
- 🌐 **Interactive Q&A system** for discussions  
- 🆔 UUID-based unique identifiers for data  
- 🔒 CORS protection and environment variable security  

---

## 🖥️ Installation

1. **Clone the repository**  

```bash
git clone https://github.com/your-username/evangadi-forem.git
cd evangadi-forem
```

Install dependencies
```bash
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../clint
npm install
```
## Create environment variables
Create a .env file in the server directory:

```ini
DB_HOST=your_mysql_host
DB_USER=your_mysql_user
DB_PASSWORD=your_mysql_password
DB_NAME=your_database_name
JWT_SECRET=your_jwt_secret
```

## Start development servers
```bash
# Start backend server
cd server
npm run dev

# Start frontend server
cd ../clint
npm start
```
## 🔧 Available Scripts

Server

`npm run dev` - Start development server

`npm start` - Start production server

Client

`npm start` - Start development server

## 🔒 Security Features

JWT-based authentication

Password hashing with bcrypt.js

CORS protection

Environment variable protection

## 📝 License

This project is licensed under the ISC License.
