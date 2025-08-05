# 🍽️ Aahar Link

**Aahar Link** is a web-based food redistribution platform that connects surplus food donors (e.g., restaurants, individuals) with verified receivers (NGOs, shelters). It aims to combat food waste and support food security by building a reliable and real-time bridge between the two.

---

## 🚀 Features

### 👤 Role-Based Interfaces
- **Donor Portal**
  - `donor_login.html` & `donor_dashboard.html`
  - Post food donations, track status, and view request history
- **Receiver Portal**
  - `receiver_login.html` & `receiver_dashboard.html`
  - Browse active listings, request food, rate donors
- **Customer (Admin/Coordinator) View**
  - Moderate the ecosystem, verify users, manage conflicts

### 📩 Dynamic Features
- JavaScript-powered real-time DOM updates
- Form validation and responsive interactions
- Individual CSS + JS logic per role for modularity

---

## 🛠 Tech Stack

| Layer      | Stack / Tools                   |
|------------|----------------------------------|
| **Frontend** | HTML5, CSS3, Vanilla JS |
| **Backend**  | Node.js, Express.js            |
| **Data**     | JSON-based mocks (or plug MongoDB) |
| **Foldering** | Role-based segregation (donor, receiver, customer) |
| **Deployment** | Render / Node Hosting-ready |

---

## 🧩 Folder Structure

aahar-link/
├── backend/
│ └── public/
│ ├── donor_login.html / donor_dashboard.html
│ ├── receiver_login.html / receiver_dashboard.html
│ ├── customer_login.html / customer_dashboard.html
│ ├── donor.js / donor.css
│ ├── receiver.js / receiver.css
│ ├── customer.js / customer.css
│
└── README.md


- Each role has its **dedicated HTML, JS, and CSS** files to ensure clean separation of logic and responsibilities.

---

## ⚙️ How to Run Locally

```bash
# Clone the repository
git clone https://github.com/yourusername/aahar-link.git
cd aahar-link/backend

# Install dependencies
npm install

# Start the server
node server.js

🎯 Goals & Impact
Tackle hunger by bridging donors and those in need in real-time

Minimize food waste through an accessible, tech-first approach

Empower NGOs to directly reach food providers

Simplify UX with clean dashboards per user role


## 🧩 Folder Structure

