<div align="center">

  <h1>🍔 Restaurant Ordering System</h1>

  <p><strong>A modern QR-based digital ordering experience built for restaurants.</strong></p>

  <p>
    <a href="#-overview">Overview</a> •
    <a href="#-key-features">Key Features</a> •
    <a href="#-user-flow">User Flow</a> •
    <a href="#-screenshots">Screenshots</a> •
    <a href="#-technology">Technology</a> •
    <a href="#-customization-guide">Customization</a> •
    <a href="#-roadmap">Roadmap</a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Status-In_Development-8A2BE2?style=for-the-badge" alt="Status: In Development" />
    <img src="https://img.shields.io/badge/License-Proprietary-black?style=for-the-badge" alt="License: Proprietary" />
    <img src="https://img.shields.io/badge/Platform-Web_%2F_Mobile-5865F2?style=for-the-badge" alt="Platform: Web / Mobile" />
  </p>

  ---

</div>

## 📌 Overview

The **Restaurant Ordering System** is a modern, responsive web application designed to bridge the gap between traditional dining and digital convenience. By leveraging table-specific QR codes, the system allows customers to view a digital menu, select categorized items, add special instructions, and submit orders directly to restaurant staff.

For restaurant operations, the system includes a dedicated **Staff Dashboard** to generate table QR codes in bulk and monitor incoming live orders with real-time status updates, streamlining table service and kitchen operations.

---

## ✨ Key Features

* 📱 **Table-Specific QR Code Generation:** Automated generation and download of table-bound QR codes with batch printing options.
* 📖 **Categorized Digital Menu:** Clean display of menu items across categories (Starters, Main Course, Pizza & Pasta, Burgers, Desserts, Drinks) with descriptions and prices.
* 🛒 **Order Customization & Cart:** Dynamic cart functionality with quantity adjustments, itemized subtotals, and custom notes for special requests or allergies.
* 🖥️ **Live Staff Admin Dashboard:** Real-time dashboard for kitchen and staff to manage live orders, filter by order status (*New*, *Preparing*, *Ready*, *Delivered*), and transition items through preparation phases.
* ⚡ **Real-Time Backend Communication:** Terminal and server-side socket integration handling table connections, order broadcasts, and database persistence instantly.

---

## 🔄 User Flow

<p>[ 📲 Scan Table QR Code ]</p>
│
▼
<p>[ 📋 Browse Digital Menu ]</p>
│
▼
<p>[ 🛒 Select Items & Add Notes ]</p>
│
▼
<p>[ 📝 Place Order (Pay at Cashier) ]</p>
│
▼
<p>[ 🔔 Staff Dashboard Receives Live Order ]</p>
│
▼
<p>[ 🍳 Staff Updates Status: Preparing ➔ Delivered ]</p>


---

## 📸 Screenshots

> **Note:** To ensure images render properly, upload your screenshot files to your repo's `screenshots/` folder or drag and drop them directly into the GitHub web editor.

### 1. Table QR Code Generator
Staff can specify the number of tables and auto-detect server address to generate and download individual or batch printable QR codes.

<img width="1351" height="605" alt="qr-generator" src="https://github.com/user-attachments/assets/3433686a-b322-4d9c-9d35-b3c2fe885766" />

*Staff dashboard interface showing auto-detected server address and table QR code batch generation.*

---

### 2. Customer Digital Menu
Customers scan their table's QR code to view the menu categorized into Starters, Main Course, Pizza & Pasta, Burgers, Desserts, and Drinks.

<img width="1348" height="605" alt="customer-menu" src="https://github.com/user-attachments/assets/8939da05-b7a9-4a8e-b419-d359f8f69b57" />

*Digital menu interface displaying table location, category tabs, item pricing, and item descriptions.*

---

### 3. Shopping Cart & Special Requests
Customers can review selected items, adjust quantities, calculate exact order totals, and attach special requests or allergy notes before ordering.

<img width="417" height="601" alt="cart-ordering" src="https://github.com/user-attachments/assets/c760b7cc-847d-4971-ac0d-db97b8ab57d8" />

*Order summary modal featuring quantity selectors, special instructions input, total pricing, and cashier payment prompt.*

---

### 4. Live Staff Orders Dashboard (Empty State)
The live staff dashboard awaiting new incoming customer orders in real-time.

<img width="1364" height="605" alt="admin-dashboard-empty" src="https://github.com/user-attachments/assets/8edffad8-2a30-4e1e-8d55-3466aa0f4017" />

*Staff dashboard interface showing live status indicators and empty order state.*

---

### 5. Live Staff Orders Dashboard (Active Order)
A central management view for staff displaying incoming orders sorted by table number, time, items, special notes, and status controls.

<img width="1119" height="466" alt="admin-orders-active" src="https://github.com/user-attachments/assets/947b26f2-810a-44b3-ab6c-c252f570ff6d" />

*Staff dashboard rendering real-time incoming orders with status filters (New, Preparing, Ready, Delivered) and status progression buttons.*

---

### 6. Application Server & Real-Time Terminal
Server console tracking database connections, real-time client socket connections, order generation per table, and admin events.

<img width="971" height="491" alt="server-terminal" src="https://github.com/user-attachments/assets/917c9342-338e-40c3-b4c5-0a17d57cf650" />

*Terminal runtime displaying active network addresses, database initialization, and real-time order emission logs.*

---

## 🛠️ Technology

| Layer | Technology / Tools |
| :--- | :--- |
| **Frontend** | HTML5 / CSS3 / JavaScript |
| **Backend & Real-Time** | Node.js / Express / WebSockets |
| **Database** | Database Persistence Layer |

---

## 📖 Customization Guide

To enable easy modification of restaurant logos, table configurations, and menu items without altering core application logic, a dedicated customization guide was created.

* 📄 **Document:** Customization & Implementation Manual (`.pdf`)
* 📍 **Location:** `docs/customization-guide.pdf` *(Available upon request)*
* 💡 **Scope:** Detailed steps on adjusting branding elements, configuring network bindings, and updating menu data.

---

## 🚀 Roadmap & Future Development

- [x] QR code generator dashboard for staff
- [x] Table-bound digital menu browsing
- [x] Order cart with special requests and allergies field
- [x] Real-time live orders dashboard for staff/kitchen
- [x] Customization guide documentation (PDF)
- [ ] **Easy Customization Software:** Graphical tool for restaurant managers to edit menu items and prices visually without manual configuration
- [ ] Direct online payment portal integration
- [ ] Kitchen printer auto-print integration
- [ ] Multi-language support for customer menus

---

## 🎯 Project Goals

1. **Practical Application:** Deliver a practical, production-ready system to modernise in-restaurant ordering workflows.
2. **Commercial Deployment:** Build a solid foundation suitable for deployment as a commercial service for small-to-medium restaurants.
3. **Seamless UX:** Provide a frictionless ordering experience for customers and an intuitive operational view for staff.

---

## 🔒 Source Code & Licensing

The source code for this project is currently private as it is being actively developed for potential commercial deployment. 

For inquiries regarding demonstrations, licensing, or commercial deployment, feel free to contact me using the details below.

---

## 👨‍💻 Developer

**Sedrat Abdelmoumene**  
*Web Developer & Creative Problem-Solver*

I specialize in modern web development, software engineering, and building useful interactive web tools.

| Channel | Link |
| :--- | :--- |
| **GitHub** | [@Sedrat-Abdelmoumene](https://github.com/Sedrat-Abdelmoumene) |
| **Email** | [abdelmoumenesedrat@gmail.com](mailto:abdelmoumenesedrat@gmail.com) |
| **WhatsApp** | [+213 794 868 404](https://wa.me/213794868404) |

---

<div align="center">
  <p>© 2026 Sedrat Abdelmoumene. All rights reserved.</p>
</div>
