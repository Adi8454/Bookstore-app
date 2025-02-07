# Bookstore App (MERN Stack)

## 📖 Overview

The **Bookstore App** is a full-stack web application built using the **MERN stack (MongoDB, Express, React, Node.js)**. This app allows users to browse, add, update, and delete books. Users can also create an account, log in, and manage their personal book collection.

## 🚀 Features

- **User Authentication**: Sign up, log in, and manage user accounts.
- **Book Management**: Add, update, delete, and view books.
- **Search & Filter**: Easily find books using search and filter options.
- **Cart System**: Add books to the cart and proceed to checkout.
- **Admin Panel**: Manage books and users (admin access only).
- **Responsive Design**: Optimized for both desktop and mobile devices.

## 🛠 Tech Stack

- **Frontend**: React.js, Redux, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose ORM)
- **Authentication**: JSON Web Token (JWT), bcrypt.js
- **API Testing**: Postman

## 📂 Project Structure

```
bookstore-app/
│-- backend/         # Express.js server
│   │-- models/      # Mongoose schemas
│   │-- routes/      # API endpoints
│   │-- controllers/ # Business logic
│   │-- config/      # Database connection
│   │-- server.js    # Main entry point
│
│-- frontend/        # React.js application
│   │-- src/
│   │   │-- components/   # UI Components
│   │   │-- pages/        # Page components
│   │   │-- redux/        # State management
│   │   │-- App.js        # Main React component
│
│-- .env             # Environment variables
│-- package.json     # Project dependencies
│-- README.md        # Project documentation
```

## 🚀 Installation & Setup

### **1. Clone the Repository**

```sh
git clone https://github.com/your-username/bookstore-app.git
cd bookstore-app
```

### **2. Install Dependencies**

#### Backend

```sh
cd backend
npm install
```

#### Frontend

```sh
cd ../frontend
npm install
```

### **3. Configure Environment Variables**

Create a **.env** file in the `backend/` directory and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

### **4. Run the Application**

#### Start Backend Server

```sh
cd backend
npm start
```

#### Start Frontend

```sh
cd frontend
npm start
```

The app will be available at http\://localhost:5173/admin

## 📸 Screenshots



## 📜 API Endpoints

| Method | Endpoint        | Description               |
| ------ | --------------- | ------------------------- |
| GET    | /api/books      | Get all books             |
| POST   | /api/books      | Add a new book            |
| GET    | /api/books/\:id | Get book details          |
| PUT    | /api/books/\:id | Update book information   |
| DELETE | /api/books/\:id | Delete a book             |
| POST   | /api/users      | Register a new user       |
| POST   | /api/auth       | User login/authentication |

## 📌 Future Enhancements

- Implement payment gateway for book purchases.
- Add book reviews and ratings.
- Implement wishlists and book recommendations.
- Deploy the app to production using **Vercel/Heroku**.

## 📜 License

This project is licensed under the MIT License.

## 💡 Contributing

Contributions are welcome! Feel free to **fork the repo**, create a **pull request**, or **open an issue**.

## 🙌 Acknowledgments

- [MongoDB](https://www.mongodb.com/)
- [Express.js](https://expressjs.com/)
- [React.js](https://reactjs.org/)
- [Node.js](https://nodejs.org/)

---

**👨‍💻 Developed by Aditya Kumar**

