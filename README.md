# Guidewire-hackathon

🚀 GigShield AI
AI-Powered Parametric Insurance for India’s Gig Delivery Workers


📌 Problem State\ment

India’s gig delivery workers (Zomato, Swiggy, etc.) depend on daily earnings. External disruptions like heavy rain, extreme heat, pollution, or curfews reduce their working hours, leading to 20–30% income loss.

Currently, there is no system that protects their income during such uncontrollable events.

🎯 Our Solution

GigShield AI is an AI-powered parametric insurance platform that:

Provides weekly income protection plans

Uses real-time external data (weather, AQI, etc.)

Automatically detects disruptions

Instantly triggers payouts without manual claims

👉 Focus: Income loss only (NO health, NO vehicle, NO accidents)

👤 Target Persona

Food Delivery Partners (Zomato / Swiggy)

Why this persona?

Highly affected by weather conditions

Work outdoors → direct impact from disruptions

Weekly earning cycle → fits our pricing model

⚙️ Core Features
🧑‍💻 1. User Onboarding

Mobile number + OTP login

Basic profile:

Name

City

Platform (Zomato / Swiggy)

Optional KYC (basic verification)

📊 2. User Dashboard

Displays:

Weekly earnings estimate

Active insurance plan

Risk level (Low / Medium / High)

Weather/AQI alerts

Claim history

Wallet balance

💸 3. Weekly Insurance Plans
Plan	Premium	Coverage
Basic	₹20/week	₹200 payout
Standard	₹30/week	₹300 payout
Premium	₹50/week	₹500 payout

👉 Premium is dynamically adjusted using AI risk score

⚠️ 4. Smart Risk Alerts (AI Feature)

“High Rain Risk Tomorrow 🌧️”

“Extreme Heat Warning 🔥”

“Severe Pollution Alert 🌫️”

👉 Helps users take proactive decisions

💰 5. Wallet System

Add money (UPI / mock payment)

Deduct premium weekly

Receive payouts instantly

Transaction history

📜 6. Claims System (Fully Automated)

No manual claim filing

Claims triggered automatically based on events

Status:

Processing

Approved

Rejected

🌍 7. Admin Dashboard

Total users

Active policies

Claims triggered

Fraud detection logs

Zone-based heatmaps

⚡ Parametric Triggers (Core Logic)

Claims are triggered based on real-world data:

Trigger Type	Condition	Payout
Rain	Rainfall > 50mm	Yes
Heat	Temperature > 45°C	Yes
Pollution	AQI > 400	Yes
Social	Curfew / strike	Yes
🔄 Workflow
User buys weekly plan →
System monitors APIs →
Disruption detected →
Claim auto-created →
Fraud checks →
Instant payout to wallet
🤖 AI/ML Integration
🧠 1. Risk Prediction Model

Purpose: Predict disruption probability

Model: Logistic Regression / Random Forest

Inputs:

City

Historical weather

AQI

Season

Output:

Risk Score (0–1)

💰 2. Dynamic Pricing Model

Purpose: Adjust weekly premium

Premium = Base Price + (Risk Score × Factor)

Model: Linear Regression / XGBoost

🚨 3. Fraud Detection Model

Purpose: Detect fake claims

Model: Isolation Forest

Checks:

Location mismatch

Duplicate claims

Abnormal claim patterns

🔗 API Integrations

🌦️ Weather API (OpenWeatherMap / Mock)

🌫️ AQI API (CPCB / Mock)

🚦 Traffic API (Mock)

💳 Payment API (Razorpay / Mock)

🏗️ System Architecture
Frontend (React)
     ↓
Backend (Spring Boot)
     ↓
Database (PostgreSQL)
     ↓
ML Service (Python)
     ↓
External APIs (Weather, AQI, Payments)
🛠️ Tech Stack
Frontend

React (Vite)

CSS / Tailwind

Backend

Spring Boot

REST APIs

JWT Authentication

Database

PostgreSQL

Machine Learning

Python

scikit-learn

Pandas

Payment Integration

Razorpay / UPI (or mock)

🧩 Unique Features (Innovation)

🔮 AI-based risk alerts before disruption

🤖 Smart plan recommendation

📉 Income loss estimator

🗺️ Area-based risk heatmaps

🎮 Gamification (badges for insured users)

📅 Development Plan
Week 1–2

UI + Backend setup

Authentication system

Week 3

API integration

Trigger monitoring

Week 4

ML models implementation

Week 5

Payment + wallet system

Week 6

Dashboard + optimization

🎥 Demo Plan (2-Min Video)

Explain problem (income loss)

Show dashboard

Show buying plan

Simulate trigger → show auto payout

✅ Key Highlights

✔ Fully automated system
✔ Weekly pricing model
✔ AI-driven risk + pricing
✔ Instant payouts (no claims process)
✔ Real-world data integration

📌 Conclusion

GigShield AI provides a simple, scalable, and intelligent safety net for India’s gig workers. By combining AI, real-time data, and parametric insurance, it ensures workers are financially protected from unpredictable disruptions.
"# GigSheildAi" 
