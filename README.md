# OTT Plan Recommender – Frontend 🎬

A React-based web application that helps users choose the most suitable OTT subscription plans based on their preferences and content usage. This is the frontend of the OTT subscription recommendation system.

---

## Features

- Upload content usage files for analysis
- Get personalized plan recommendations based on:
  - Price
  - Video quality
  - Device usage
- Simple and responsive user interface
- Connects to a Spring Boot backend via REST API

---

## Tech Stack

Frontend: React.js  
Styling: CSS, Bootstrap  
HTTP Requests: Axios  
Package Manager: npm

---

## Folder Structure

ott-subscription-client-main/  
├── public/  
├── src/  
│   ├── components/  
│   │   ├── TextExtract.js  
│   │   ├── BestPlan.js  
│   │   └── ...  
│   ├── App.js  
│   └── index.js  
├── package.json  
└── README.md  

---

## Setup Instructions

1. Clone the repository:

   git clone git@github.com:dhruvilad34/ott-subscription-client.git  
   cd ott-subscription-client

2. Install dependencies:

   npm install

3. Start the development server:

   npm start

The app will run locally at: http://localhost:3000  
Ensure the backend is running on http://localhost:8080

---

## API Endpoints Used

- POST /api/analyze-file  
- GET /api/best/price  
- GET /api/best/videoquality

---

## Backend Repository

Repository Name: acc-subscription-backend

