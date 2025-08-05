# 🍱 Aahar Link — Bridging Hunger with Surplus

Aahar Link is a full-stack web application that connects food donors (such as restaurants, cafes, and households) with receivers (NGOs, shelters, and individuals in need). By facilitating real-time food sharing and logistics, it aims to reduce food waste and ensure edible surplus food reaches those who need it most.

---

## 🚀 Key Features

### 👨‍🍳 Donor Dashboard
- Post surplus food listings with quantity, expiry time, and pickup details
- Approve incoming requests from verified receivers
- Track past donations and complaints
- Real-time rating updates based on receiver feedback

### 🧍 Receiver Dashboard
- Browse available food listings
- Send real-time requests to donors
- Get notified instantly upon approval (includes donor contact and location)
- Rate donors post pickup to ensure quality and reliability

### 🔔 Real-Time Notifications
- WebSockets or dynamic polling to instantly reflect new approvals, messages, and status updates for both donors and receivers.

### 📊 Dynamic Rating System
- Receiver can rate donors after each donation
- Donor ratings update dynamically on their profile cards

### 🖼️ Hero Section (Landing Page)
- Responsive carousel with images and call-to-actions
- Sections like "What We Do" and "How Can You Help?" to onboard new users

---

## 🧠 Future AI/ML Integrations (Planned)

- **Donation Demand Prediction** using historical trends
- **Smart Matching Engine** to pair specific types of food with high-need zones
- **Food Freshness Prediction** based on listing timestamps and categories

---

## 🛠 Tech Stack

| Tech        | Description                           |
|-------------|---------------------------------------|
| **MongoDB** | NoSQL database for storing users, listings, and ratings |
| **Express.js** | Backend REST API & authentication logic |
| **React**   | Interactive front-end SPA for both donor and receiver views |
| **Node.js** | Server-side runtime environment |
| **Tailwind CSS** | Rapid UI styling with utility-first classes |
| **Vanilla JS** | Real-time DOM updates and form validations |
| **Socket.io / Polling** | Real-time updates and notifications |
| **Vite** | Lightning-fast React development setup |

---

## 📦 Folder Structure

```bash
Aahar-Link/
│
├── client/                  # React frontend
│   ├── pages/               # Home, Login, Dashboards
│   ├── components/          # Navbar, Notifications, Cards
│   └── assets/              # Images and icons
│
├── api/                     # Node.js + Express backend
│   ├── routes/              # API routes for users, food, auth
│   ├── controllers/         # Logic for handling requests
│   ├── models/              # MongoDB schemas
│   └── middleware/          # Auth, validation, etc.
│
└── README.md
