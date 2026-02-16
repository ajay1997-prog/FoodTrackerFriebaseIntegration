# 🌿 NourishDaily: Professional Food Tracker

[![Firebase](https://img.shields.io/badge/Firebase-Real--time-FFCA28?logo=firebase&logoColor=white)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Interface: Nature](https://img.shields.io/badge/Interface-Nature--Theme-2E7D32)](#)

NourishDaily is a high-performance, aesthetically pleasing food tracking application designed to help users scale their nutrition with precision. Featuring real-time cloud synchronization and a unique time-based meal locking mechanism, it ensures disciplined and accurate logging of daily habits.

---



## ✨ Key Features

### ☁️ Real-time Cloud Sync
Powered by **Firebase Realtime Database**, every entry and status update is instantly synchronized across all devices. No manual saving required.

### 🛡️ Secure Access
A simple but effective 4-digit passcode system protects your nutritional data from unauthorized local access.

### 📄 Professional Reporting
One-click print functionality generates a clean, nature-themed report of your day's nutrition, perfect for sharing with healthcare professionals or maintaining physical logs.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3 (Custom Variables, Flexbox/Grid), JavaScript (Vanilla ES6+)
- **Backend/Database**: Firebase Realtime Database
- **Icons & Fonts**: Font Awesome 6.0, Google Fonts (Merriweather, Nunito)

---

## 📂 Project Structure

```text
Food Tracker/
├── foodtracker/
│   ├── index.html    # Main dashboard implementation
│   ├── style.css     # Nature-themed design system
│   ├── script.js    # Core logic & Firebase integration
│   └── .git/         # Version control metadata
└── README.md         # Documentation (this file)
```

---

## 🚀 Getting Started

### 1. Prerequisites
- A modern web browser.
- A Firebase project for data persistence.

### 2. Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/food-tracker.git
   ```
2. Open `foodtracker/index.html` in your browser.

### 3. Firebase Configuration
Update the `firebaseConfig` object in `foodtracker/script.js` with your project credentials:
```javascript
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
    databaseURL: "https://YOUR_PROJECT_ID.firebaseio.com",
    // ... rest of your config
};
```

---

## 🎨 Design Philosophy
NourishDaily follows a "Nature-First" design philosophy, utilizing a palette of leafy greens, soft earthy tones, and glassmorphism effects to create a calming, professional environment for nutritional tracking.

---

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

