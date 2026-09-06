# 🌍 Tourably

### Explore More. Discover Better. Travel Smarter.

**A smart tourism and travel platform for exploring popular and hidden destinations in Satara, discovering travel packages, and simplifying booking inquiries.**

---

## 📖 About the Project

**Tourably** is a smart tourism and travel platform designed to help users explore both popular and hidden destinations in **Satara, Maharashtra**, and discover travel packages that suit their interests.

Planning a trip often requires searching across different websites and platforms for destinations, routes, packages, and booking information. Tourably brings these travel-related features together in one place to provide a more convenient and user-friendly experience.

Users can explore tourist destinations, discover travel packages, view location and route information, and connect for booking inquiries through WhatsApp. The platform also includes secure user authentication, an AI-powered chatbot, and an admin dashboard for managing platform-related information.

> 🎓 **Tourably was developed as an academic project to demonstrate practical web development, cloud services, API integration, and tourism information management.**

---

## ✨ Features

### 👤 User Features

- 🔐 User Signup and Login
- 🏠 Interactive Homepage
- 🗺️ Explore Popular Tourist Destinations
- 🌿 Discover Hidden Places in Satara
- 🎒 Browse Travel Packages
- 📍 View Location and Route Information
- 🧭 Google Maps/My Maps Integration
- 📱 WhatsApp-Based Booking Inquiries
- 🤖 AI-Powered Travel Assistance Chatbot
- 📋 Travel and Tourism Information
- 📱 User-Friendly and Responsive Interface

### 👨‍💼 Admin Features

- 📊 Admin Dashboard
- 📋 Manage Booking Information
- 🎒 Manage Travel Packages
- 🗺️ Manage Tourist Destinations
- 🛣️ Manage Routes
- 💰 Manage Fees and Related Information
- 📝 Manage Platform Data

---

## 🔄 How Tourably Works

```
Visit Tourably
    │
    ▼
Signup / Login
    │
    ▼
Explore the Platform
    │
    ├───────────────┬────────────────┬────────────────┐
    ▼               ▼                ▼                ▼
Explore Places   Travel Packages   Services      AI Chatbot
    │               │
    ▼               ▼
View Locations   Select Package
and Routes            │
    │                ▼
    │         Booking Inquiry
    │                │
    │                ▼
    │        WhatsApp Opens
    │                │
    │                ▼
    │        Send Booking Request
    │
    ▼
Plan Your Visit
```

---

## 🏗️ System Overview

```
👤 USER
        │
        ▼
┌───────────────────────┐
│       TOURABLY        │
│   Web Application     │
└───────────┬───────────┘
            │
    ┌───────┼──────────────┐
    │       │              │
    ▼       ▼              ▼
Firebase  Google Maps /  WhatsApp
Auth      Google My Maps  Booking
    │
    ▼
Cloud Firestore
    │
    ▼
Admin Dashboard

🤖 AI-Powered Chatbot
    │
    ▼
Travel Assistance
```

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| 🌐 HTML5 | Website structure and content |
| 🎨 CSS3 | Styling and responsive design |
| ⚡ JavaScript | Interactivity and client-side functionality |
| 🔥 Firebase Authentication | User authentication and account management |
| 🗄️ Cloud Firestore | Database management |
| 🗺️ Google Maps / My Maps | Location and route information |
| 📱 WhatsApp Integration | Booking inquiries and communication |
| 🤖 AI Integration | Travel assistance chatbot |
| 📄 PapaParse | CSV data handling |
| 💻 Visual Studio Code | Development environment |

---

## 🌍 Explore Satara

Tourably helps users discover and learn about tourism destinations in and around Satara.

Users can explore:

- 🏔️ Popular tourist destinations
- 🌿 Hidden and less-explored places
- 📍 Destination locations
- 🛣️ Routes and travel information
- ℹ️ Useful destination details

The goal is to make it easier for visitors to discover the tourism opportunities available in Satara.

---

## 🎒 Travel Packages

Users can browse available travel packages and choose options based on their travel interests.

Package information may include:

- 📦 Package Name
- 📍 Destination
- 📅 Duration
- 💰 Package Price
- 🎯 Included Services
- 🛣️ Travel Information

---

## 📱 Booking Process

Tourably uses WhatsApp for booking inquiries and communication.

```
Select a Travel Package
        │
        ▼
    Click Book Now
        │
        ▼
   WhatsApp Opens
        │
        ▼
Pre-filled Booking Message
        │
        ▼
   User Sends Inquiry
        │
        ▼
Booking Communication Begins
```

> ⚠️ Tourably currently does not process online payments directly through the platform.

---

## 🤖 AI-Powered Chatbot

Tourably includes an AI-powered chatbot to assist users with travel-related questions.

The chatbot can help users with:

- 💬 General tourism queries
- 🗺️ Destination-related information
- 🧳 Travel planning assistance
- 📍 Tourist place guidance
- ❓ General user queries

---

## 🔐 Authentication

Tourably uses Firebase Authentication to manage user accounts.

Users can:

- Create an account
- Log in securely
- Access authenticated features
- Manage their user session

---

## 👨‍💼 Admin Dashboard

The Admin Dashboard helps manage important platform-related information.

Administrators can manage:

- 📋 Booking information
- 🎒 Travel packages
- 📍 Tourist destinations
- 🛣️ Routes
- 💰 Fees
- 📝 Other platform data

---

## 📂 Project Structure

```
Tourably/
│
├── index.html
├── login.html
├── signup.html
├── explore.html
├── packages.html
├── services.html
│
├── admin/
│   └── dashboard.html
│
├── css/
│   ├── style.css
│   └── responsive.css
│
├── js/
│   ├── script.js
│   ├── firebase-config.js
│   ├── auth.js
│   ├── chatbot.js
│   └── admin.js
│
├── assets/
│   ├── images/
│   └── icons/
│
└── README.md
```

> Note: The actual project structure may differ depending on the final implementation.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/tourably.git
```

### 2. Open the Project

Open the project folder using Visual Studio Code or your preferred code editor.

### 3. Configure Firebase

Create a Firebase project and configure:

- Firebase Authentication
- Cloud Firestore

Add your Firebase configuration to the appropriate configuration file.

Example:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

> ⚠️ Never upload private API keys, credentials, or sensitive configuration files to a public repository.

### 4. Configure Integrations

Configure the required integrations used in your project, such as:

- 🔥 Firebase
- 🗺️ Google Maps / Google My Maps
- 📱 WhatsApp booking link
- 🤖 AI API for chatbot functionality

### 5. Run the Project

Run the project using a local development server.

For example:

- VS Code Live Server
- Any compatible local web server

---

## 🎯 Project Objectives

Tourably aims to:

1. Make tourism information easier to access.
2. Help users discover popular and hidden destinations in Satara.
3. Provide travel package information in one platform.
4. Simplify booking communication through WhatsApp.
5. Improve travel planning using modern web technologies.
6. Digitally promote tourism destinations in Satara.

---

## 🔮 Future Improvements

Future versions of Tourably may include:

- 💳 Secure Online Payment Integration
- ⭐ Ratings and Reviews
- 📅 Real-Time Package Availability
- 🏨 Hotel and Accommodation Booking
- 🚗 Transportation Integration
- ❤️ Save Favourite Destinations
- 🧠 Personalized Travel Recommendations
- 📱 Dedicated Mobile Application
- 🌐 Multi-Language Support
- 📊 Advanced Admin Analytics

---

## 🎓 Academic Project

Tourably was developed as an academic project to demonstrate practical implementation of:

- Web Development
- User Authentication
- Cloud Database Integration
- API Integration
- AI Integration
- Maps and Location Services
- Third-Party Communication Integration

---

## 👨‍💻 Developer

**Swayam Chorge**

Computer Science and Engineering Student

📌 GitHub: https://github.com/swayamchorge 

📧 Email: chorgeswayam2006@gmail.com

🔗Linkedln: https://www.linkedin.com/in/swayam-chorge-a01214432

---

## 📄 License

This project is currently intended for educational and academic purposes.

Third-party services, APIs, maps, and technologies used in this project are subject to their respective terms and licenses.

---

<div align="center">

## 🌍 Tourably

### Explore More. Discover Better. Travel Smarter.

⭐ If you found this project interesting, consider giving the repository a star!

</div>

