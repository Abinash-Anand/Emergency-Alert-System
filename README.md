# 🌍 RapidReach - Emergency Reporting & Response Platform

## 💡 Project Overview

Emergency alert system (EAS) is a real-time emergency reporting and response web application that empowers users to quickly report emergencies, alert others, and assist those in need.
It combines geolocation services, SOS alerts, live emergency tracking, and AI voice assistance for enhanced emergency management.

---

## 🔗 Key Features

1. **Report Emergencies:**

   - Drag the marker to the exact location.
   - Select emergency type (Fire, Medical, Security, Natural Disaster, Other).
   - Provide a description manually or via voice assistant.

2. **Real-time Dashboard:**

   - View nearby emergencies instantly on a map.
   - See detailed emergency cards with time, address, and responder counts.

3. **SOS Button:**

   - Instantly send your live location with an SOS alert for urgent help.

4. **Emergency Details Page:**

   - Track routes to emergencies with directions.
   - View/respond to emergencies and mark status (Arrived, Resolved, Cancelled).

5. **Profile Management:**

   - View availability, phone number, emergency skills.
   - Track your emergency response history.

6. **Voice Assistant Integration:**
   - Report emergencies hands-free by recording descriptions.

---

## 🌐 Technologies Used

- **Frontend:** React.js, TailwindCSS, MapboxGL
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Real-time Features:** Socket.IO (for SOS alerts)
- **Voice Assistant:** Web Speech API

---

## 🔖 Setup Instructions

1. **Clone the repository:**

```bash
git clone <your-repo-link>
cd rapid-reach-frontend
```

2. **Install dependencies:**

```bash
npm install
```

3. **Set up environment variables:**
   Create a `.env` file and add your Mapbox token:

```
VITE_MAPBOX_ACCESS_TOKEN=your_mapbox_token_here
```

4. **Start the development server:**

```bash
npm run dev
```

> Make sure backend server (API) is running separately.

---

## 🏆 Bonus Features Implemented

- [x] Project Pitch Slide Deck
- [x] Live SOS Button
- [x] Voice-powered Emergency Reporting
- [x] Real-time Emergency Updates

---

## 💡 Why We Built It

Emergencies require speed, clarity, and accessibility. RapidReach ensures that:

- **Anyone** can report an emergency in seconds.
- **First responders** get live, detailed updates.
- **Communities** can coordinate better in critical situations.

---

## 🔍 Future Improvements

- Push Notifications for SOS alerts.
- Role-based access for Admins/Responders.
- Offline capabilities for low network areas.
- AI-based automatic emergency detection from user voice.

---
