# JuaConnect - Skilled Labor Marketplace 🛠️

A hyper-local marketplace connecting Jua Kali artisans (plumbers, electricians, mechanics) with clients in real-time. Architected for high concurrency, security, and location-based discovery.

![MERN Stack](https://img.shields.io/badge/MERN-Full%20Stack-success?style=for-the-badge&logo=react)
![Status](https://img.shields.io/badge/Status-Production%20v1.2-blue?style=for-the-badge)

## 🚀 Technical Architecture

This project utilizes a decoupled **Client-Server** architecture using the latest stable builds (**React 19** + **Express 5**).

### 🎨 Frontend (Client)
Built for speed and responsiveness.
- **Framework:** React 19 (Concurrent Mode enabled)
- **Styling:** TailwindCSS 3.4 (Utility-first architecture)
- **Routing:** React Router DOM 6+
- **HTTP Client:** Axios (Interceptors for global error handling)
- **Testing:** React Testing Library

### 🔐 Backend (API)
Engineered for security and scalability.
- **Runtime:** Node.js + Express 5.1 (Beta)
- **Database:** MongoDB + Mongoose 8.2 (Data Modeling)
- **Security:** - `Helmet` (HTTP Header hardening)
  - `Express-Rate-Limit` (DDoS protection)
  - `BcryptJS` (Password Hashing)
  - `JWT` (Stateless Authentication with HttpOnly cookies)
- **Logging:** Winston (Production-grade transport logging)

## 📦 System Capabilities
1.  **Geospatial Search:** MongoDB `$near` queries to find artisans within a 5km radius.
2.  **Real-time Status:** Express Async Handler for non-blocking I/O operations.
3.  **Role-Based Access:** Distinct portals for **Clients** (Buyers) and **Artisans** (Sellers).
4.  **Audit Logs:** Full system tracing for dispute resolution.

---
*© 2025 JuaConnect Systems. All Rights Reserved.*
