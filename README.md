# LIBRARY-MANAGEMENT-SYSTEM
A full-stack library Management System built with Node.js, Express, MongoDB, and EJS. Includes user authentication, admin dashboard, and book borrowing features.
Excellent 👍 Here’s a **ready-to-use and well-formatted `README.md`** file for your project **LIBRARY-MANAGEMENT-SYSTEM** — written in professional GitHub markdown style with badges, sections, and everything you need.

You can **copy and paste this entire content** into your project’s root folder as a file named **`README.md`**.

---

````markdown
# 📚 Library Management System

A full-stack **Library Management System** built with **Node.js**, **Express**, **MongoDB**, and **EJS**.  
This application helps manage a library efficiently by providing features for **book management**, **user authentication**, and **admin control**.  

---

## 🚀 Features

- **User Authentication**: Secure login and signup using sessions and flash messages.
- **Book Management**: Add, edit, delete, and search books by title, author, genre, or ISBN.
- **Borrow & Return System**: Users can borrow books and view their borrow history.
- **Admin Dashboard**: Admins can manage users, books, and monitor activities.
- **Responsive UI**: Fully mobile-friendly interface built with Bootstrap and EJS templates.
- **Database Integration**: MongoDB used for data persistence and MySQL2 for optional relational data support.

---

## 🧰 Tech Stack

| Layer | Technology Used |
|-------|-----------------|
| **Frontend** | EJS, Bootstrap, Font Awesome |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (Mongoose ORM), MySQL2 |
| **Authentication** | express-session, connect-flash |
| **Environment Management** | dotenv |

---

## ⚙️ Installation Guide

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/LIBRARY-MANAGEMENT-SYSTEM.git
cd LIBRARY-MANAGEMENT-SYSTEM
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Create Environment File

Create a `.env` file in the project root and add:

```
MONGO_URI=mongodb://127.0.0.1:27017/libraryDB
SESSION_SECRET=your-secret-key
```

### 4. Run MongoDB

Make sure MongoDB service is running:

```bash
mongod
```

### 5. Start the Application

```bash
npm start
```

Server will start at **[http://localhost:8080](http://localhost:8080)**

---

## 🖥️ Usage

* **Home Page**: Displays library overview and features.
* **User Login/Register**: Access user-specific book operations.
* **Book Operations**: Search, borrow, or return books.
* **Admin Panel**: Manage users, add/remove books, and view analytics at `/admin`.

---

## 📁 Project Structure

```
LIBRARY-MANAGEMENT-SYSTEM/
├── app.js                   # Main application entry point
├── package.json             # Dependencies and scripts
├── config/
│   └── db.js                # Database connection setup
├── models/
│   ├── userModel.js         # User schema
│   ├── bookModel.js         # Book schema
│   └── adminModel.js        # Admin schema
├── routes/
│   ├── index.js             # Main router
│   ├── auth/                # Authentication routes
│   ├── admin/               # Admin routes
│   ├── books/               # Book-related routes
│   └── general/             # General routes
├── views/
│   ├── index.ejs            # Homepage
│   ├── profile.ejs          # User profile
│   └── partials/            # Shared templates (navbar, footer)
├── public/                  # Static files (CSS, JS, images)
└── middleware/              # Custom middleware files
```



## 🪪 License

This project is licensed under the **ISC License**.
Feel free to use and modify it for educational or commercial purposes.

---

## 📸 Screenshots 
📷 /public/screenshots/
- login.png
<img width="1197" height="821" alt="image" src="https://github.com/user-attachments/assets/f0010d33-b64a-4c32-ac21-ac2050674bc9" />

- dashboard.png
- <img width="1200" height="606" alt="image" src="https://github.com/user-attachments/assets/cc97bacf-068c-4fa7-96d7-04380ce58b16" />
- user management.png
- <img width="1196" height="328" alt="image" src="https://github.com/user-attachments/assets/20398c49-69b8-447f-acbd-2ee1cc0bed35" />
- book-list.png
- <img width="1199" height="659" alt="image" src="https://github.com/user-attachments/assets/92337f44-27ee-45a7-a695-fc8afa993cd9" />
  <img width="1173" height="306" alt="image" src="https://github.com/user-attachments/assets/4c602ee1-9114-4570-9cab-69da119ee84f" />


```


💬 Author

👤 Ashish
📧 ashish.maurya17000@gmail.com
🌍 [GitHub Profile](https://github.com/<your-username>)



⭐ **If you like this project, don’t forget to give it a star on GitHub!** ⭐


Would you like me to **add GitHub badges** (like Node.js, MongoDB, License, etc.) at the top of this README for a more professional look?
```
