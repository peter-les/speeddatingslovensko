# Speed Dating Bratislava

A simple web application for managing and running speed dating events in Bratislava. The project handles event listings, payment flow, seat availability tracking, and post-payment registration.

## 🌐 Live Demo
https://peter-les.github.io/speeddatingslovensko/

## 📌 Project Overview

This project was built as a lightweight event management system for speed dating sessions. It allows users to:

- View upcoming speed dating events
- See available seats by gender and age group
- Pay for participation via Stripe Checkout links
- Register after successful payment
- Store registrations and availability data in Firebase Realtime Database

The system is designed as an MVP (Minimum Viable Product) for real-world use in small event operations.

## ⚙️ Features

- Event listing by age groups
- Real-time seat tracking (Firebase Realtime Database)
- Stripe Checkout payment integration (hosted payment links)
- Post-payment registration form
- Basic validation of paid users before registration
- Simple responsive UI (HTML/CSS/JavaScript)

## 🧠 Architecture

- **Frontend:** HTML, CSS, Vanilla JavaScript
- **Backend (BaaS):** Firebase Realtime Database
- **Payments:** Stripe Checkout (hosted payment links)
- **Hosting:** GitHub Pages

## 🔄 System Flow

1. User selects an event and pays via Stripe link  
2. Payment is processed externally by Stripe  
3. After payment, user is redirected to registration page  
4. System checks Firebase for payment confirmation  
5. User fills in registration form  
6. Data is stored in Firebase Realtime Database  

## 🗄️ Data Storage

Firebase is used for:
- Tracking available seats per event
- Storing payment status flags
- Storing user registrations

## ⚠️ Security Notes

- Payment processing is handled by Stripe Checkout (no card data is stored or processed in this application)
- Firebase is used as a lightweight backend; security rules should be configured for production use
- This project is intended as an MVP / prototype system

## 🚀 Technologies Used

- HTML5 / CSS3
- JavaScript (Vanilla)
- Firebase Realtime Database
- Stripe Checkout
- GitHub Pages

## 📈 Purpose

This project demonstrates:
- Practical web application development
- Integration of external services (Stripe, Firebase)
- Basic event management system design
- Frontend + cloud backend integration without traditional server

## 👤 Author

GitHub: https://github.com/peter-les/  
YouTube: https://www.youtube.com/@PeterLes11  

## 📄 License

This project is for demonstration and portfolio purposes.
