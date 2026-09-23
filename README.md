# 🎨 ARTE – Art Shopping Website

**ARTE** is a modern, responsive online art marketplace where users can explore, save, add to cart, and purchase different types of artworks.

## ✨ Features

* 🔐 User Sign Up and Login
* 🚪 User Logout
* 🖼️ Art Gallery
* 🔎 Artwork Search
* 🏷️ Category Filtering
* ❤️ Wishlist / Saved Artworks
* 🛒 Shopping Cart
* 💳 Checkout
* 📦 Order History
* 👤 User Profile
* 👨‍🎨 Artist Information
* 🔥 Firebase Authentication
* ☁️ Firebase Firestore
* 🖼️ Firebase Storage
* 🛠️ Admin Dashboard
* ➕ Add New Artworks
* ✏️ Edit Artworks
* 🗑️ Delete Artworks
* 📋 Manage Orders
* 📱 Responsive Design

## 🎨 Artwork Categories

ARTE supports the following artwork categories:

* Paintings
* Digital Art
* Sculptures
* Photography
* Abstract Art
* Traditional Art

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* React.js
* Firebase Authentication
* Firebase Firestore
* Firebase Storage

## 🔥 Firebase Integration

Firebase is used for:

### Authentication

Email and password authentication for users.

### Firestore

Stores:

* Users
* Artworks
* Orders
* Wishlist information

### Firebase Storage

Stores artwork images uploaded by the administrator.

## 📁 Project Structure

```text
arte-art-shopping-website/
│
├── public/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── firebase/
│   ├── assets/
│   ├── App.jsx
│   └── main.jsx
│
├── .env.example
├── .gitignore
├── package.json
├── README.md
└── ...
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/arte-art-shopping-website.git
```

Open the project:

```bash
cd arte-art-shopping-website
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

## 🔑 Firebase Configuration

Create a Firebase project and enable:

* Firebase Authentication
* Email/Password Authentication
* Firestore Database
* Firebase Storage

Add your Firebase configuration through environment variables.

Example:

```text
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

**Never upload your real `.env` file or private credentials to GitHub.**

## 👨‍💼 Admin

The admin dashboard allows authorized administrators to:

* Upload artworks
* Edit artworks
* Delete artworks
* Manage artwork information
* View orders
* Update order status

Admin access should be controlled using the user's Firebase/Firestore role.

## 🛒 Shopping Flow

```text
Home
 ↓
Gallery
 ↓
Artwork Details
 ↓
Add to Cart
 ↓
Cart
 ↓
Checkout
 ↓
Order Confirmation
 ↓
Order History
```

## 📱 Responsive Design

ARTE is designed to work on:

* Desktop
* Laptop
* Tablet
* Mobile

## 🚀 Future Improvements

* Online payment gateway
* Artist accounts
* Artist dashboard
* Product reviews and ratings
* Advanced recommendation system
* Order tracking
* Email notifications
* AI-powered artwork recommendations

## 📄 License

This project is developed for educational and portfolio purposes.

---

### 🎨 ARTE

**Where Art Meets Expression**
