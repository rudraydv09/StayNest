# 🏡 StayNest – Full Stack Vacation Rental Platform

StayNest is a full-stack vacation rental platform that allows users to explore, create, and manage property listings with secure authentication, interactive maps, image uploads, reviews, and advanced search functionality.

## 🚀 Live Demo

🔗 https://staynest-qw7o.onrender.com/listings

## 📖 About

StayNest is designed to provide a seamless property rental experience where users can browse accommodations, list their own properties, upload images, view locations on interactive maps, and leave reviews. The application follows the MVC architecture and implements secure authentication and authorization practices.

---

## ✨ Features

### 🔐 Authentication

* User Signup
* User Login
* User Logout
* Secure Password Hashing
* Session-based Authentication using Passport.js

### 🏠 Listings

* Create New Listings
* Edit Existing Listings
* Delete Listings
* View Individual Listing Details

### ☁️ Image Management

* Cloudinary Image Upload
* Image Storage & Management
* Multer Integration

### 🗺️ Maps

* Interactive Property Maps
* Location Visualization

### ⭐ Reviews

* Add Reviews
* Delete Reviews
* Ratings System

### 🔎 Search

* Search by Title
* Search by Location
* Search by Country

### 🛡️ Authorization

* Only Owners Can Edit Listings
* Only Owners Can Delete Listings
* Protected Routes

### ✅ Validation

* Server-side Validation using Joi
* Custom Error Handling
* Invalid Route Handling (404)

### 🎨 UI

* Responsive Design
* Flash Messages
* Mobile Friendly Interface

---

## 🛠 Tech Stack

### Frontend

* HTML5
* CSS3
* Bootstrap 5
* JavaScript
* EJS

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* Passport.js
* Passport Local
* Passport Local Mongoose
* Express Session
* Connect Flash

### Validation

* Joi

### File Upload

* Multer
* Cloudinary

### Maps

* Mapbox

### Deployment

* Render

---

## 📂 Project Structure

```text
StayNest/
│
├── controllers/
├── middleware/
├── models/
├── routes/
├── utils/
├── public/
├── views/
├── cloudConfig.js
├── schema.js
├── app.js
└── package.json
```

---

## ⚙️ Installation

```bash
git clone https://github.com/rudraydv09/staynest.git
cd staynest
npm install
```

Create a `.env` file:

```env
ATLASDB_URL=your_mongodb_connection_string
CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
MAP_TOKEN=your_mapbox_access_token
SECRET=your_session_secret
```

Run the project:

```bash
npm start
```

or

```bash
nodemon app.js
```

---

## 📌 Future Enhancements

* Property Booking System
* Payment Gateway Integration
* Wishlist Feature
* Host Dashboard
* Real-Time Chat
* Email Notifications

---

## 👨‍💻 Author

**Rudra Pratap Singh Yadav**

* GitHub: https://github.com/rudraydv09
* LinkedIn: https://linkedin.com/in/rudra0912
