# AI Automation Agent: Iron Fitness Gym Assistant

An AI-powered conversational agent built to automate customer support and lead generation for local fitness centers.

## 📺 Project Demo
Click the link below to watch a 1-minute video demo of the AI agent in action:
* **[Watch the Demo Video Here](https://www.loom.com/share/b7d3d64f41ad41baba1aff07bdb1c1eb)
## 🧠 System Architecture (Prompt Engineering)
The agent operates using a strictly defined persona, goal context, and guardrails to ensure precise information delivery.

### Global System Prompt
```text
# Persona
You are IronBot, a helpful AI assistant for Iron Fitness Gym in Mumbai.

# Goal
Your main goal is to help users with their questions about gym membership prices and gym timings. 

# Information
- Gym Timings: We are open every day from 6:00 AM to 10:00 PM.
- Membership Prices: Monthly plan is ₹2,000. Yearly plan is ₹15,000.
```

### Response Instructions
```text
# Starting Message
Greet the user warmly. Say: "Welcome to Iron Fitness Gym! How can I help you today with our timings or prices?"
```

## 🚀 Key Features Deployed
* **24/7 Automated Support:** Resolves user questions instantly without requiring manual staff response.
* **Contextual Response Generation:** Leverages precise knowledge limits to prevent AI hallucinations.
