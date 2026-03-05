# GigShield – Income Protection for Delivery Partners

## Problem Statement
Many delivery partners working with apps like Zomato, Swiggy, Blinkit, and Zepto depend on daily deliveries to earn money. However, their work is strongly affected by outside conditions such as heavy rain, extreme heat, floods, high pollution, or sudden curfews. During these situations they cannot complete deliveries and their earnings drop for that day or week.

At present, most gig workers do not have a simple insurance system that protects them when they lose income because of these uncontrollable events. Our project focuses on solving this problem.

## Our Idea
We plan to build a platform called **GigShield** that helps delivery workers protect their income when external disruptions stop them from working.

The platform will monitor real-world conditions such as weather or environmental alerts using external data sources. If a disruption crosses a defined limit (for example heavy rainfall or dangerous pollution levels), the system will automatically trigger a claim and provide compensation to the affected worker.

The goal is to create a simple and automated insurance system where workers do not need to manually request claims.

## Target Persona
Our solution mainly focuses on **food delivery partners** who work for platforms such as:

- Zomato
- Swiggy
- Blinkit
- Zepto

These workers rely on daily deliveries to earn money. When external problems occur, their work hours reduce and their income is affected.

## Workflow of the Application
1. A delivery worker registers on the platform.
2. The worker chooses a weekly insurance plan.
3. The system evaluates the risk level of the worker’s location.
4. Based on the risk, a weekly premium is calculated.
5. The platform continuously checks weather and disruption data.
6. When a disruption is detected, the system automatically activates a claim.
7. The worker receives compensation through a digital payment method.

## Weekly Premium Model
Our insurance plan follows a **weekly pricing model** since gig workers usually earn money on a weekly basis.

Example:

- Weekly premium: ₹20 – ₹40  
- Compensation during disruption: ₹200 – ₹500

The premium amount can vary depending on:

- Location of the worker
- Weather risk in that area
- Historical data about disruptions

This makes the system fair and affordable for workers.

## Parametric Triggers
The platform will trigger claims automatically when certain conditions are detected. Some examples include:

- Heavy rainfall beyond a defined limit
- Extremely high temperature
- Severe air pollution (high AQI levels)
- Flood alerts
- Government curfew or restricted delivery zones

These events can be detected using external APIs or simulated data during development.

## AI / ML Integration
Artificial Intelligence will support different parts of the system.

### Risk Assessment
AI models can analyze past weather data and identify which locations have higher risk of disruptions.

### Dynamic Premium Calculation
The weekly premium can be adjusted depending on predicted risk levels in a specific area.

### Fraud Detection
The system can detect unusual activity such as incorrect location data or repeated suspicious claims.

## Technology Stack

Frontend  
- React.js

Backend  
- Spring Boot (Java)

Database  
- MySQL

External APIs  
- Weather API  
- Traffic or disruption data (mock data during development)

Payment System  
- Razorpay (test mode)

AI / ML Tools  
- Python (for basic prediction and fraud detection models)

## Development Plan

Week 1
- Study the problem and understand gig workers' challenges
- Select the target persona
- Design the system architecture
- Prepare a simple UI prototype

Week 2
- Build the user registration module
- Implement insurance policy creation
- Develop disruption monitoring logic

## Future Scope
In the future, the platform can be expanded further by:

- Supporting grocery and e-commerce delivery workers
- Integrating real delivery platform APIs
- Improving AI models for better risk prediction
- Creating dashboards for workers and insurance providers

## Team Members
1. G. Meena Chowdari  
2. Suravarapu Amrutha Varshini  
3. Pabbati Sreeja  
4. Puvvada Lakshmi Sri Durga Niharika
