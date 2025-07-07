# 🏡 StayNest

**StayNest** is a web application designed to help users find, review, and add cozy accommodation options with ease.

---

## 🚀 Live Demo
*Coming soon — your app’s URL when deployed!*

---

## 📋 Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Usage](#usage)

---

## 🔍 Features
- 🔎 Search listings by name, location or type  
- 🗺️ View listings on an interactive map  
- ⭐ Add reviews and ratings  
- ➕ Add new accommodations (if registered)  
- 📱 Responsive UI, works well on desktop and mobile  

---

## 🧰 Tech Stack
- **Frontend:** EJS templates, HTML, CSS, JavaScript  
- **Backend:** Node.js, Express  
- **Database:** MongoDB (via Mongoose)  
- **Image Hosting:** Cloudinary or similar service  
- **Auth & Sessions:** Express-session / Passport (optional)  
- **Linting / Formatting:** ESLint, Prettier  

---

## 🗂 Project Structure
StayNest/
├── controllers/ # Request handlers
├── models/ # Mongoose schemas (Listing, User, Review)
├── routes/ # Express routes
├── views/ # EJS templates (home, listing, add-form, etc.)
├── public/ # Static files (CSS, client JS, images)
├── utils/ # Helper functions
├── middleware.js # Custom middleware (auth, error handling)
├── app.js # Express setup & server initialization
├── cloudConfig.js # Configuration for image uploads
├── Schema.js # …
└── .env.example # Environment variables template

---

## 🖥 Usage

- **Guests**: Browse available stays and read reviews.
- **Registered users**: Log in to add new listings and leave reviews.
- **Adding accommodation**: Visit “Add New” page, fill out details, and upload visuals.
- **Reviewing**: Navigate to a listing page to submit ratings and feedback.


---
