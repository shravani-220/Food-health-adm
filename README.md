# CraveDecode – AI Craving Intelligence System

## 🚀 Problem Statement
Unhealthy eating is often driven by emotional and behavioral triggers rather than real hunger. Most food apps focus on calories instead of understanding *why* cravings happen. There is a need for a smart system that decodes craving psychology and guides healthier decisions.

## 💡 Solution
CraveDecode is a behavioral AI-powered web application that analyzes:
- Type of craving
- Mood
- Hunger level
- Time of day
- Sleep quality

It classifies the craving into:
- Emotional Reward
- Energy Compensation
- Habit-Based
- Dopamine-Seeking
- Genuine Hunger

## 🧠 Core Features
- Multi-step interactive UI
- Rule-based behavioral intelligence engine
- Impulse Risk Score (Low / Medium / High)
- Smart healthier alternative suggestions
- Habit correction tips
- Input validation and edge-case handling
- Modular and efficient code structure

## 🏗 Architecture
The application follows a modular structure:
- `detectCravingType()`
- `calculateImpulseRisk()`
- `generateSmartAlternative()`
- `generateHabitTip()`

Logic is rule-based for MVP efficiency and scalability.

## ♿ Accessibility
- High-contrast UI
- Large readable fonts
- Clear labels and buttons
- Keyboard-friendly interaction

## 🧪 Testing Scenarios

**Test Case 1:**  
Sweet + Stressed + Low Hunger → Emotional Reward (High Risk)

**Test Case 2:**  
Sweet + Tired + Medium Hunger → Energy Compensation (Medium Risk)

**Test Case 3:**  
Night + Low Hunger → Habit-Based Craving (Medium Risk)

**Test Case 4:**  
High Hunger (4–5) → Genuine Hunger (Low Risk)

## 🌍 Deployment
Deployed on Google Cloud Run.

---

Built for AI-based Food & Health Challenge 2026.
