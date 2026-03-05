# GigShield – AI Powered Insurance for Delivery Workers

## Problem Statement
Delivery partners working for platforms like Zomato, Swiggy, Amazon and Zepto often lose income because of external disruptions such as heavy rain, extreme heat, pollution or curfews. When these events occur, they cannot work and their daily earnings are reduced. Currently, there is no simple insurance system that protects their income during these situations.

## Our Idea
We propose an AI-powered parametric insurance platform called **GigShield**.  
This platform protects delivery workers from income loss caused by external disruptions like weather conditions or restricted zones.

The system automatically detects disruptions using external data (weather APIs, traffic data etc.). When a disruption occurs, the platform automatically triggers a claim and provides compensation to the worker.

## Target Persona
Our primary users are **food delivery partners** working on platforms like:
- Zomato
- Swiggy
- Blinkit
- Zepto

These workers depend on daily deliveries to earn money. If they cannot work because of external events, their income decreases.

## Workflow of the Application
1. Delivery worker registers in the platform.
2. Worker selects a weekly insurance plan.
3. The AI system calculates the weekly premium based on risk factors.
4. The system monitors external conditions such as weather or pollution.
5. If a disruption is detected, the claim is automatically triggered.
6. The worker receives compensation through digital payment.

## Weekly Premium Model
The insurance works on a **weekly pricing model**.

Example:

- Weekly premium: ₹20 – ₹40
- If disruption occurs, worker receives compensation of ₹200 – ₹500 depending on coverage.

The premium may change based on:
- Location
- Weather risk
- Historical disruption data

## Parametric Triggers
The system automatically triggers claims when certain conditions occur:

- Heavy Rainfall above threshold
- Extreme Heat
- Severe Air Pollution (High AQI)
- Flood warnings
- Government curfew or zone closure

These triggers are detected using external APIs and data sources.

## AI / ML Integration
Artificial Intelligence will be used for:

### Risk Assessment
Predict the risk level of a location based on historical weather and disruption data.

### Dynamic Premium Calculation
Adjust the weekly premium depending on predicted risk.

### Fraud Detection
Detect suspicious claims using anomaly detection and location validation.

## Technology Stack

Frontend  
- React.js (Web Application)

Backend  
- Node.js / Express

Database  
- MongoDB

APIs  
- Weather API
- Traffic API (mock data)

Payments  
- Razorpay (sandbox mode)

AI/ML  
- Python (Scikit-learn / simple ML models)

## Development Plan

Week 1
- Research problem
- Define persona
- Design system architecture
- Create UI prototype

Week 2
- Develop basic registration system
- Implement insurance policy creation
- Create disruption detection logic

## Future Scope
- Expand to grocery and e-commerce delivery workers
- Integrate real-time platform APIs
- Improve AI risk prediction models
- Provide dashboard for insurers and workers

## Team Members
1. G. Meena chowdari
2. Suravarapu Amrutha Varshini
3. Pabbati Sreeja
4. Puvvada Lakshmi Sri Durga Niharika
