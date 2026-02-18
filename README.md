# AI Weather & Utility Agent (n8n)

## 📌 Overview
This project is an AI-powered n8n workflow that acts as an intelligent chat assistant.  
It processes user chat messages and dynamically decides which tools to use in order to generate accurate and context-aware responses.

The agent integrates:
- 🌤 Weather API
- 💱 Currency Conversion
- 🌍 Country Information API
- 🧮 Calculator Tool
- 🧠 Memory for context retention
- 🤖 OpenAI Chat Model

---

## 🚀 How It Works

1. The workflow is triggered when a chat message is received.
2. The AI Agent processes the message using an OpenAI Chat Model.
3. Based on user intent, it selects the appropriate tool:
   - `get_weather` → Retrieves real-time weather data.
   - `convert_currency` → Converts between currencies.
   - `get_country_info` → Fetches country-related information.
   - `Calculator` → Performs mathematical calculations.
4. The agent uses memory to maintain conversation context.
5. A structured and intelligent response is generated for the user.

---

## 🎯 Problem It Solves

- Eliminates the need for multiple separate tools.
- Automates decision-making for API usage.
- Provides real-time utility data in a conversational format.
- Maintains context for smarter multi-step conversations.

---

## 🛠 Technologies Used

- n8n
- OpenAI Chat Model
- External APIs (Weather, Currency, Country Info)
- AI Agent + Tool Calling
- Simple Memory Node

---

## 📈 Future Improvements

- Add more tools (flight prices, hotel APIs, maps, etc.)
- Improve memory persistence (database storage)
- Add authentication layer
- Deploy as a public chatbot interface

---
