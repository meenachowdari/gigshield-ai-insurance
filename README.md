# GigShield – Income Protection for Delivery Partners

## Problem
Many delivery workers who work with apps like Zomato, Swiggy, Blinkit and Zepto earn money by completing deliveries every day. Their income depends on how many deliveries they can finish.

But sometimes external situations such as heavy rain, floods, extreme heat, high pollution, or sudden curfews stop them from working. During these situations they cannot complete deliveries and they lose their daily income.

Right now most gig workers do not have a simple system that protects their earnings during these disruptions. Our project tries to solve this problem.

---

## Our Idea
We want to build a platform called **GigShield** that protects delivery workers from income loss when outside events stop them from working.

The system will check weather and environmental conditions using external APIs. If a serious disruption happens (for example heavy rain or dangerous pollution levels), the system will automatically trigger a claim and give compensation to the worker.

The main goal is to create a **simple and automatic insurance system** where workers do not need to manually apply for claims.

---

## Target Users
Our project mainly focuses on **food delivery workers** who work on platforms such as:

- Zomato
- Swiggy
- Blinkit
- Zepto

These workers depend on daily deliveries for their income, so any outside disruption directly affects their earnings.

---

## How the Application Works
1. A delivery worker registers on the GigShield platform.
2. The worker selects a weekly insurance plan.
3. The system checks the worker's location to understand the risk level.
4. Based on the risk, the weekly premium is calculated.
5. The platform continuously monitors weather and disruption data.
6. If a disruption is detected, the system automatically starts a claim.
7. The worker receives the compensation through digital payment.

---

## Weekly Premium Model
Our insurance system works on a **weekly plan** because gig workers usually earn money every week.

Example:

- Weekly premium: ₹20 – ₹40  
- Compensation during disruption: ₹200 – ₹500  

The premium may change based on:

- Worker location  
- Weather risk in that area  
- Past disruption data  

This helps keep the insurance affordable for workers.

---

## Disruption Triggers
Claims will be triggered automatically when certain conditions happen, such as:

- Heavy rainfall above a certain limit  
- Very high temperature  
- Severe air pollution (high AQI)  
- Flood alerts  
- Government curfew or delivery restrictions  

During development we may use **weather APIs or simulated data**.

---

## AI / ML Usage
Artificial Intelligence will help improve the system.

### Risk Prediction
AI can analyze past weather data to identify areas where disruptions happen frequently.

### Premium Calculation
AI can adjust the weekly premium depending on the risk level of a location.

### Fraud Detection
The system can detect suspicious activities like incorrect location data or repeated fake claims.

---

## Technology Stack

Frontend  
React.js

Backend  
Spring Boot (Java)

Database  
MySQL

External APIs  
Weather API  
Traffic or disruption data

Payment System  
Razorpay 

AI / ML Tools  
Python for prediction and fraud detection

---

## Development Plan

### Week 1
- Understand the problem faced by delivery workers
- Define the target users
- Design the system architecture
- Create a simple UI prototype

### Week 2
- Build the user registration system
- Implement insurance plan creation
- Develop disruption detection logic

---

## Future Improvements
In the future the platform can be expanded to:

- Support grocery and e-commerce delivery workers
- Connect with real delivery platform APIs
- Improve AI models for better prediction
- Provide dashboards for workers and insurers

---

## Team Members
1. G. Meena Chowdari  (Team Leader)
2. Suravarapu Amrutha Varshini  
3. Pabbati Sreeja  
4. Puvvada Lakshmi Sri Durga Niharika
