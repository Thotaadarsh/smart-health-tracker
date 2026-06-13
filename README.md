# 🩺 Smart Health Tracker

<div align="center">

### 🚀 AI-Powered Smartwatch Health Monitoring System

Track your health in real-time with smartwatch integration, intelligent analytics, and personalized health insights.

![React](https://img.shields.io/badge/React-19-blue?logo=react)
![Firebase](https://img.shields.io/badge/Firebase-Backend-orange?logo=firebase)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

## 📖 Overview

Smart Health Tracker is a modern web application designed to monitor and analyze health metrics collected from smartwatches and wearable devices.

The platform provides real-time visualization of vital health data, historical trend analysis, health alerts, and user-friendly dashboards to help users stay informed about their well-being.

---

## ✨ Features

### ❤️ Real-Time Health Monitoring

* Heart Rate Tracking
* Body Temperature Monitoring
* Step Count Analysis
* Live Health Data Updates

### 📊 Interactive Dashboard

* Modern UI
* Real-Time Charts
* Health Statistics Overview
* Quick Health Summary

### 🚨 Smart Alerts

* Abnormal Heart Rate Detection
* Critical Health Notifications
* Personalized Warning System
* Emergency Monitoring Support

### 📈 Historical Analysis

* Health Data History
* Trend Visualization
* Progress Tracking
* Long-Term Health Insights

### ⚙️ User Settings

* Profile Management
* Notification Preferences
* Device Configuration
* Personalized Dashboard Settings

---

## 🏗️ System Architecture

```text
Smartwatch Device
        │
        ▼
   Health API
        │
        ▼
    Firebase
        │
        ▼
 React Frontend
        │
        ▼
 User Dashboard
```

---

## 🛠️ Tech Stack

### Frontend

* ⚛️ React.js
* 🎨 CSS3
* 🔄 React Router DOM
* 📊 Chart.js
* 📈 React ChartJS 2

### Backend & Database

* 🔥 Firebase
* ☁️ Firestore Database
* 🔐 Firebase Authentication

### Development Tools

* 🟢 Node.js
* 📦 npm
* 💻 Visual Studio Code

---

## 📂 Project Structure

```text
smart-health-tracker/
│
├── public/
│   ├── index.html
│   ├── manifest.json
│   └── robots.txt
│
├── src/
│   ├── components/
│   │   ├── Dashboard.js
│   │   ├── Alerts.js
│   │   ├── History.js
│   │   ├── Settings.js
│   │   └── HealthMetric.js
│   │
│   ├── screens/
│   │   ├── DashboardScreen.js
│   │   ├── AlertsScreen.js
│   │   ├── HistoryScreen.js
│   │   └── SettingsScreen.js
│   │
│   ├── services/
│   │   └── healthService.js
│   │
│   ├── firebase.js
│   ├── App.js
│   └── index.js
│
├── package.json
└── README.md
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/Thotaadarsh/smart-health-tracker.git
```

### Navigate to Project

```bash
cd smart-health-tracker
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm start
```

Application will be available at:

```text
http://localhost:3000
```

---

## 🔥 Firebase Setup

### Step 1: Create Firebase Project

1. Visit Firebase Console
2. Create a New Project
3. Enable Firestore Database
4. Enable Authentication

### Step 2: Configure Firebase

Update:

```javascript
src/firebase.js
```

with your Firebase credentials:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
};
```

---

## 📊 Dashboard Modules

### 🏠 Dashboard

Displays:

* Current Heart Rate
* Body Temperature
* Daily Steps
* Health Overview

### 🚨 Alerts

Displays:

* Health Warnings
* Critical Notifications
* Emergency Alerts

### 📈 History

Displays:

* Previous Health Records
* Daily Trends
* Weekly Reports
* Monthly Analytics

### ⚙️ Settings

Allows users to:

* Configure Alerts
* Manage Devices
* Customize Dashboard
* Update Preferences

---

## 🎯 Future Enhancements

* 🤖 AI-Based Health Prediction
* 📱 Mobile Application
* ⌚ Multi-Wearable Support
* 🏥 Doctor Consultation Integration
* 📍 GPS Emergency Tracking
* ☁️ Cloud Analytics
* 🧠 Machine Learning Health Insights

---

## 📸 Screenshots

Add screenshots here:

```text
screenshots/
├── dashboard.png
├── alerts.png
├── history.png
└── settings.png
```

---

## 🧪 Available Scripts

### Start Development Server

```bash
npm start
```

### Run Tests

```bash
npm test
```

### Build for Production

```bash
npm run build
```

### Eject Configuration

```bash
npm run eject
```

---

## 🌟 Why This Project?

This project demonstrates:

✅ React Development

✅ Firebase Integration

✅ Health Monitoring Systems

✅ Data Visualization

✅ Smart Device Connectivity

✅ Real-Time Analytics

✅ Modern UI/UX Design

---

## 👨‍💻 Author

### Thota Adarsh

📧 Email: [adarshthota61@gmail.com](mailto:adarshthota61@gmail.com)

🔗 GitHub: https://github.com/Thotaadarsh

---

## 🤝 Contributions

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It helps support future development and encourages open-source contributions.

---

## 📜 License

This project is developed for educational and research purposes.

© 2025 Smart Health Tracker. All Rights Reserved.
