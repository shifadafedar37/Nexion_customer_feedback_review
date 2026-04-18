InsightIQ – Customer Review Intelligence Platform
📌 Overview

InsightIQ is an AI-powered retail analytics platform that transforms raw, unstructured customer reviews into actionable business insights.

It processes reviews in real-time, performs multilingual sentiment analysis, detects patterns, and provides feature-level insights through an interactive dashboard.

🎯 Problem Statement

Customer reviews are:

Unstructured and messy
Multilingual and inconsistent
Difficult to analyze at scale

Most existing systems only:

Summarize reviews ❌
Miss deeper insights ❌

👉 Challenge:
Build a system that can:

Handle real-world noisy data
Extract feature-level sentiment
Detect trends and patterns over time
Provide actionable recommendations
💡 Solution

InsightIQ solves this by:

Processing large-scale review data in real-time
Performing AI-based sentiment classification
Extracting feature-level insights (price, delivery, performance, etc.)
Detecting:
Complaints
Praise trends
Sarcasm & spam
Delivering results through an interactive dashboard
👥 Target Audience
🛒 E-commerce & D2C Brands – manage customer reviews
📊 Product Managers – improve product features
📣 Marketing Teams – understand brand perception
📈 Business Analysts – track trends
🎧 Customer Support Teams – resolve recurring issues
⚙️ Core Features
🔄 Real-Time Processing
Live review ingestion using WebSockets
Instant updates on dashboard
🌍 Multilingual Support
Handles reviews in multiple languages
Preprocessing and normalization
🤖 AI-Powered Sentiment Analysis
Positive
Negative
Neutral
Spam detection
🧩 Feature-Level Analysis
Price
Delivery
Performance
Quality
📊 Interactive Dashboard
KPI cards
Sentiment charts
Live feedback stream
🎤 Voice Assistant
Accepts voice commands
Converts speech → text → processing
📂 Data Upload Pipeline
Upload CSV / JSON
Automatic processing
🚨 Advanced Detection
Sarcasm detection
Spam filtering
Anomaly detection
🛠️ Technology Stack
Frontend
React (Vite)
Tailwind CSS
Backend
Node.js
Express.js
Real-Time Communication
Socket.io (WebSockets)
AI / NLP
Gemini API (Generative AI)
NLP processing
Database
Firebase Firestore
🏗️ System Architecture
User (Dashboard UI)
        ↓
React Frontend
        ↓
Node.js Backend (API + Socket.io)
        ↓
AI Processing Layer (NLP + Gemini API)
        ↓
Firebase Firestore (Database)
📸 Key Modules (from PPT)
📊 Dashboard
Overview of KPIs
Total reviews, sentiment ratio
🤖 Sentiment Analyzer
Classifies reviews
Shows feature-based insights
🔴 Live Feedback Stream
Real-time incoming reviews
Instant classification
🎤 Voice Assistant
Hands-free command input
📂 Data Upload System
Upload review datasets
Automated processing
🚀 Getting Started
1️⃣ Clone Repository
git clone https://github.com/your-username/insightiq.git
cd insightiq
2️⃣ Install Dependencies
npm install
3️⃣ Run Backend
npm run server
4️⃣ Run Frontend
npm run dev
🔑 Environment Variables

Create a .env file:

FIREBASE_API_KEY=your_key
FIREBASE_PROJECT_ID=your_project_id
GEMINI_API_KEY=your_api_key
📊 Workflow
Upload reviews (CSV/JSON)
System processes data
AI analyzes sentiment & features
Results shown on dashboard
Business takes action
🏆 Hackathon Details
Event: Hack Malenadu '26
Domain: Customer Retail
Team Name: Nexion
👨‍💻 Team Members
Shifa Lakshar
Madhu Ravi Kolur
Nayana V A
Meghana S
📌 Conclusion

InsightIQ transforms customer feedback into meaningful, actionable insights using AI and real-time processing.

It enables businesses to:

Understand customer sentiment
Improve products
Make faster data-driven decisions
