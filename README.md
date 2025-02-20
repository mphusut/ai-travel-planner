# 🌍 Full-Stack AI Trip Planner  
🚀 Built with React, Gemini AI, Firebase & TailwindCSS  

## 📌 Overview  
This **AI-powered trip planner** helps users generate **smart travel itineraries** using **Google APIs, Gemini AI, and Firebase**. It provides **personalized recommendations**, displays **interactive maps**, and enhances the user experience with **TailwindCSS styling**.  

---

## ✨ Features  
✅ **AI-Powered Travel Itineraries** (Google Gemini AI)  
✅ **Dynamic Google Maps Integration**  
✅ **Hotel & Place Recommendations** (Google Places API)  
✅ **Interactive UI with TailwindCSS**  
✅ **Real-Time Data Storage & Retrieval** (Firebase)  
✅ **Beautiful Laptop Mockup Preview**  

---

## 🛠️ Tech Stack  
| Technology | Usage |
|------------|----------|
| **React 19 + Vite** | Frontend Framework |
| **Google Gemini AI** | AI-based itinerary generation |
| **Firebase (Firestore, Auth, Hosting)** | Backend, Authentication, and Storage |
| **Google Maps API** | Map & location services |
| **Google Places API** | Fetching hotel & attraction details |
| **TailwindCSS** | Styling for a modern UI |
| **React Router** | Navigation between pages |

---

## 📸 Screenshots  
| Home Page | Itinerary Page | Map View |
|-----------|--------------|----------|
| ![Home](./screenshots/home.png) | ![Itinerary](./screenshots/itinerary.png) | ![Map](./screenshots/map.png) |

---

## 📦 Installation & Setup  
### 1️⃣ Clone the repository  
```sh
git clone https://github.com/yourusername/ai-trip-planner.git
cd ai-trip-planner

    2️⃣ Install dependencies

    npm install --legacy-peer-dep

    3️⃣ Set up Firebase & Google APIs
    Create a Firebase project at Firebase Console.
    Enable Firestore, Authentication, and Hosting.
    Get a Google Maps & Places API Key from Google Cloud Console.
    4️⃣ Configure environment variables
    Create a .env file in the project root and add:

    VITE_FIREBASE_API_KEY=your_firebase_api_key
    VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
    VITE_FIREBASE_PROJECT_ID=your_project_id
    VITE_GOOGLE_GEMINI_AI_API_KEY=your_google_gemini_api_key
    VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key

    5️⃣ Run the project
    
    npm run dev
    🗺️ Usage Guide
    1️⃣ Enter your destination & travel preferences
    2️⃣ AI generates a full travel itinerary
    3️⃣ View recommended hotels & attractions
    4️⃣ Explore locations on an interactive map
    5️⃣ Save your itinerary to Firebase

    
    📚 Learnings & Challenges
    ✅ Working with AI APIs (Google Gemini)
    ✅ Integrating Google Maps dynamically
    ✅ Using Firebase for real-time storage
    ✅ Building a UI with TailwindCSS

    🔗 Links & Resources
    Live Demo: https://ai-travel-planner-rust.vercel.app
    GitHub Repo: github.com/mphusut/ai-trip-planner
    Google AI Docs: Google Gemini API
    Google Maps API: Maps Platform
    Firebase Docs: Firebase Setup