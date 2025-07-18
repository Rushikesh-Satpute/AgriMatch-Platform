#  🌾 Agri Match Platform

A mobile-first platform designed to connect **fruit farmers** with **genuine wholesale buyers** using transparent pricing, location-based matching, and feedback-based trust systems. Built as a final-year engineering project, it focuses on solving real-world challenges in India's fragmented fruit supply chain using **technology, UI/UX, and cloud services**.

---

## 📱 App Screenshots

| Home Screen | Buyer Dashboard | Farmer Onboarding |
|-------------|-----------------|-------------------|
| ![Home](./screenshots/home.png) | ![Buyer](./screenshots/buyer.png) | ![Farmer](./screenshots/farmer.png) |

> *Note: These are representative screenshots. Actual flow includes dynamic pricing, inquiries, and feedback.*

---

## 🛠️ Tech Stack

**Frontend:**
- React Native
- TypeScript
- Tailwind CSS (via NativeWind)
- React Navigation, React Native Vector Icons

**Backend & Cloud:**
- Firebase Authentication
- Firestore Database (NoSQL)
- Firebase Storage
- Firebase App Check & Rules
- Firebase Cloud Messaging (FCM)

**Design & Tools:**
- Figma (UI/UX)
- Git & GitHub (Private Repository)
- VS Code, Android Studio

---

## ✨ Key Features

- ✅ **Farmer Registration & Product Listing**  
  Farmers register with location, fruit type, and quantity.

- 📍 **Buyer Discovery & Inquiry System**  
  Buyers see real-time farmer listings, send inquiries with intent & quantity.

- 📊 **Dynamic Price Meter**  
  Suggests price to farmers based on market trends (manual entry for now, ML-ready).

- ⭐ **Feedback & Rating System**  
  After delivery, buyers rate farmers. Helps build trust and quality benchmark.

- 🔒 **Role-Based Access**  
  Separate access flows for Farmers, Buyers, and Admins with permission-based UI.

- 📥 **Admin Panel (Basic)**  
  Admin can approve farmer profiles, listings, and moderate disputes.

---

## 🧠 Architecture Overview

React Native App (Farmer/Buyer)
|
Firebase Auth → Firestore (DB)
|
Firebase Storage ← Image Uploads
|
App Check → Secure Backend Calls
|
Cloud Messaging → Real-time notifications

---

## 🎯 Goals

- Solve inefficiencies in unstructured mandi ecosystem  
- Ensure verified quality supply for wholesale buyers  
- Provide farmers with pricing clarity & better market access  
- Make the platform usable on low-end phones and low-data areas

---

## 👤 Team & My Contribution

> Project developed as part of final-year major project at JSPM’s Jayawantrao Sawant College of Engineering, Pune.

**My Role (Rushikesh Satpute):**
- Lead developer (React Native & Firebase)
- UI/UX design in Figma
- Implemented Firebase Authentication & Firestore logic
- Designed role-based access and app security flow
- Integrated App Check, Notifications & Modular UI Components

---

## 📁 Repository & Access

**Repository:** Private (due to ongoing optimization & potential IP value)  
**Demo & Documentation:** Available upon request  
**Contact:** [rushikeshsatpute3558@gmail.com](mailto:rushikeshsatpute3558@gmail.com)

---

## 📌 Note to Reviewers

This project was built with real-world exposure, having tested the platform with actual fruit farmers and buyers during early stages. It reflects practical problem-solving, system design, and scalable architecture for rural tech ecosystems.

---
