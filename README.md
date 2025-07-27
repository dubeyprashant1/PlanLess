# 🌟 Planless – Make Every Hour Count

**Planless** is a smart, mood-based activity planning assistant that helps you find the perfect thing to do based on your **mood**, **budget**, and **time**—whether you’re flying solo or planning with friends. It delivers personalized, real-time suggestions that make every moment meaningful.

![Planless Banner](\IndexPage.png)

---

## 🚀 Features

- 🎯 **Personalized Plans** – Get recommendations tailored to your mood, budget, and time availability.
- 💰 **Budget-Friendly** – From free activities to premium experiences, we curate options that suit your wallet.
- 🕒 **Time-Based Suggestions** – Have 15 minutes or a full day? Planless gives the best options for any schedule.
- 🤝 **Solo or Social** – Whether you're alone or with a group, get suggestions that adapt to your company.
- 📍 **Location Aware** – Discover real-time, nearby events and activities.

---

## 🛠️ Tech Stack

| Frontend        | Backend          | Others                |
|-----------------|------------------|------------------------|
| React.js / HTML-CSS | Node.js / Express | Google places API, Google Gemini API, |

---

## 📦 Installation

Step-1 Clone the Repository

```bash
git clone https://github.com/dubeyprashant1/PlanLess.git


Step-2 Install Dependencies

```bash

cd ai-planner
npm install


Step-3 . Get Your API Keys
1. 🔑 Google Places API
2. Go to the Google Cloud Console
3. Create a new project or select an existing one.
4. Enable Places API.
5. Navigate to APIs & Services > Credentials, and generate an API Key.
6. Restrict it for web or server-side use as needed.
7. 🤖 Google Gemini API (for AI-powered suggestions)
8. Visit Google AI Studio
9. Create a project and generate your Gemini API Key.

Step-4 Set Up Environment Variables
Create .env file in the ai-planner/server directory and add:

```bash 

GOOGLE_PLACES_API_KEY=your_google_places_api_key
GEMINI_API_KEY=your_gemini_api_key

step-5 Start Development servers

```bash

#(In current terminal  --  Frontend)
npm run dev 

#(In another terminal --  Backend)
cd ai-planner/server
node index.js

#click on the link on 1st terminal(Frontend Server)

