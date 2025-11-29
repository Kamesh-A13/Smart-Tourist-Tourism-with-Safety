# Smart Tourist – Tourism with Safety  
**Smart India Hackathon 2025 | Team: Decode Warriors**

A safety-centric travel companion app for domestic and international tourists — combining secure digital identity, real-time safety alerts, geo-fencing, AI-driven SOS detection, AR navigation and multilingual support.

## 🚀 What It Does  
- Provides a blockchain-backed *Digital Tourist ID* (Aadhaar/Passport) for secure identity verification.  
- Sends alerts when entering unsafe or restricted zones via geo-fencing.  
- Detects unusual tourist behavior (route deviation, inactivity, sudden changes) to auto-trigger SOS.  
- Supports offline SOS queuing (in case of network loss).  
- Offers AR-based navigation (prototype with ARCore) + multilingual voice/text assistance.  
- Includes a backend + database to store tourist info, trips, ID and emergency contacts.

## 🔧 Tech Stack  
- **Frontend (Web):** Next.js + React.js  
- **Mobile App:** Flutter + Mapbox (offline maps) + ARCore  
- **Backend:** Node.js + Express.js (REST APIs)  
- **Database:** MySQL  
- **Extras:** Blockchain-based ID logic, offline-first design  

## 🛠️ How to Set Up Locally  

### 1. Clone the repository  
```bash

git clone https://github.com/Kamesh-A13/Smart-Tourist-Tourism-with-Safety.git
cd Smart-Tourist-Tourism-with-Safety

2. Set up Database

Create a database (e.g. tourist_db) in MySQL.

Import SQL file:

mysql -u YOUR_DB_USER -p tourist_db < tourist_db.sql


(Or use phpMyAdmin / any GUI-based DB tool.)

3. Run Backend
cd backend
npm install
npm run dev


This will start backend server (e.g. at http://localhost:5000).

4. Run Frontend (Web)
cd frontend
npm install
npm run dev


Open in browser: http://localhost:3000

✅ What’s Included

Secure Digital ID system

Geo-fencing & safety alerts

AI-based emergency detection & SOS

AR navigation prototype

Multilingual support

Basic web + mobile + backend + database

🚧 Status & Next Steps

Core features (ID, DB, backend + basic frontend) are functional.

AR navigation is prototype.

Further: UI polish, multilingual UI/UX, authority dashboard, live-tracking & heatmap, production-ready deployment.

🤝 Contributing

Feel free to fork, suggest improvements or add features — especially UI/UX enhancements, AI model tuning, AR improvements, language support, etc.
