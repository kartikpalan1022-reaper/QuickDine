## 🔗 Live Demo

Live : https://quick-dine-tan.vercel.app/

# 🍽️ QuickDine

QuickDine is a full-stack restaurant reservation platform built using the MERN stack with TypeScript. It enables customers to discover restaurants, reserve tables, and manage bookings, while providing restaurant owners and administrators with dedicated dashboards for restaurant management and booking approval.

---

## 🚀 Features

### 👤 User
- User Registration & Login (JWT Authentication)
- Browse restaurants
- Search & filter restaurants
- View restaurant details
- Book tables for available slots
- View booking history
- Cancel bookings

### 🏪 Restaurant Owner
- Create and manage restaurant
- Upload restaurant images (Cloudinary)
- Edit restaurant details
- View customer bookings
- Accept / Reject reservations
- Owner dashboard

### 🛡️ Admin
- Manage users
- Approve / Reject restaurants
- Dashboard statistics
- View latest bookings
- Manage restaurants

---

# 🛠️ Tech Stack

## Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Axios
- React Hot Toast

## Backend
- Node.js
- Express.js
- TypeScript
- MongoDB
- Mongoose
- JWT Authentication
- Multer
- Cloudinary

---

# 📂 Project Structure

```
QuickDine
│
├── client
│   ├── src
│   ├── public
│   └── ...
│
├── server
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middlewares
│   ├── config
│   └── ...
│
└── README.md
```

---

# 🔐 Authentication

- JWT Authentication
- Protected Routes
- Role Based Access
  - User
  - Owner
  - Admin

---

# 📸 Image Upload

Restaurant images are securely uploaded using:

- Multer (Memory Storage)
- Cloudinary

---

# 📅 Reservation System

Users can

- Select booking date
- Select available slot
- Reserve seats
- View booking history

Restaurant owners can

- Accept bookings
- Reject bookings
- Track reservations

---

# 🌐 Environment Variables

## Server

Create a `.env` file inside the **server** folder.

```env
MONGODB_URI=

JWT_SECRET=

CLOUDINARY_CLOUD_NAME=

CLOUDINARY_API_KEY=

CLOUDINARY_API_SECRET=

ALLOW_DESTRUCTIVE_SEED=false
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/QuickDine.git
```

---

## Backend

```bash
cd server
npm install
```

Start Server

```bash
npm run server
```

---

## Frontend

```bash
cd client
npm install
npm run dev
```

---

# 📸 Screenshots

## Home Page

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/c6845e38-6792-4236-afd8-62e0ec55af29" />

---

## Search Page

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/f48c366e-987a-4812-ac8e-52ed23da28d5" />

---

## Restaurant Details

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/34436015-b8bc-46c3-8666-9bcf3b8382cd" />

---

## Booking Page

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/97d50d0d-4a2e-4562-a50b-04f4c8a2ef91" />

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/e32edf14-86f3-47b3-8503-f5932eacda3b" />

---

## Owner Dashboard

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/2be633e4-cd0a-4b04-b3b1-b2745ff6f9fc" />

---

## Admin Dashboard

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/27ca1050-5eec-49af-b59a-b6ebbc9d7c9b" />

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/721ee7d4-d677-4248-8731-c588d51b5317" />

---

# 📈 Future Improvements

- Email Notifications
- Payment Gateway Integration
- Restaurant Ratings & Reviews
- Google Maps Integration
- Real-time Seat Availability
- Booking Reminder Notifications

---

# 📚 Learning Outcomes

This project helped me gain practical experience in:

- MERN Stack Development
- TypeScript
- REST API Design
- JWT Authentication
- Cloudinary Integration
- File Uploads
- MongoDB & Mongoose
- Role Based Authorization
- Full Stack Deployment

---

# 👨‍💻 Author

**Kartik Palan**

GitHub: https://github.com/kartikpalan1022-reaper

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
