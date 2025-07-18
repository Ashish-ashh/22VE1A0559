# 22VE1A0559
React URL Shortener Web App: https://ashish-ashh.github.io/22VE1A0559/

# 🔗 React URL Shortener Web App

![React](https://img.shields.io/badge/React-18.2.0-blue?logo=react) 
![Material UI](https://img.shields.io/badge/Material--UI-v5.14.0-blue?logo=mui) 
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 👨‍💻 Developed By

**Ashish Sriramoju**  
Final Year Engineering Student | Aspiring Data Scientist | Passionate Frontend Developer  
📧 Email: ashishsriramoju@gmail.com  
🌐 LinkedIn: [linkedin.com/in/ashish-sriramoju](https://linkedin.com/in/ashish-sriramoju)

---

## 🚀 Project Overview

This is a **React-based URL Shortener Web Application** built as part of the **Campus Hiring Evaluation Pre-Test**. It allows users to shorten URLs, optionally define custom shortcodes and validity periods, and view analytics such as click count, click source, timestamp, and approximate geolocation — all while ensuring clean, modern UI with **Material UI** components and a strong focus on **client-side logic and middleware-based logging**.

---

## 📌 Features

### ✅ URL Shortener Page
- Shorten **up to 5 URLs at once**
- Inputs:  
  - Original Long URL  
  - Optional Validity Period (in minutes) — defaults to **30 mins**  
  - Optional **Custom Shortcode** (validated for uniqueness and format)
- **Client-side validation** (URL format, validity, shortcode rules)
- Displays:
  - Shortened URL
  - Expiry time
  - Redirection functionality via **client-side routing**

### 📊 URL Statistics Page
- Shows **all shortened URLs** from session or persistent storage
- Analytics for each URL:
  - Creation & Expiry date
  - Total click count
  - **Click history** with:
    - Timestamp
    - Referrer (source)
    - Coarse-grained location (Geo info)

---

## 🧰 Tech Stack

- ⚛️ **React.js** (with React Router)
- 🎨 **Material UI** for consistent design
- 📦 **Custom Logging Middleware** (mandatory logging, no console logs)
- 🧪 Validation: native JS + helper utils
- ⛓️ **Client-Side Data Storage** (Local/session storage for analytics)

---

## 🛠️ Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/your-username/url-shortener-react.git
cd url-shortener-react

# 2. Install dependencies
npm install

# 3. Run the application
npm start

