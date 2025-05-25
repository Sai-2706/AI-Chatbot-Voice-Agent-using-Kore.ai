# AI-Chatbot-Voice-Agent-using-Kore.ai
Developed an *AI Chatbot & AI Voice Assistant* for Pronix Inc organisation using the Kore.ai platform.

# 🤖 Pronix Virtual Assistant (AI Chatbot & Voice Agent using Kore.ai)

The main aim of the project is to develop an **AI Chatbot and AI Voice Assistant** for **Pronix Inc.** organisation using the **Kore.ai platform**.

## Project Overview

*Goal*:  
Automate customer support by providing accurate, real-time responses to user queries through chat and voice interfaces — deployed using Kore.ai's enterprise AI platform.

*Tech Stack*:
- Kore.ai (Bot Builder Studio)--> ( https://platform.kore.ai/auth/login ) & ( https://academy.kore.ai/ )
- NLP / NLU (Kore’s native language engine)
- Knowledge AI (FAQs + Web crawling from [pronixinc.com](https://www.pronixinc.com))
- REST API Integration (Dialog Tasks)
- SIP IVR configuration (for voice)
- Agent Handoff with Kore Default Chat Panel

*Features Implemented*:
AI Chatbot via Website Widget  
Voice Assistant using IVR SIP (Partially Configured)  
FAQ Auto-Response (Web Crawling + Manual FAQs)  
Sentiment Detection & Fallback Handling  
Agent Escalation for Unresolved Queries  
REST API Integration Sample (APISample task)  
Feedback Collection & Ratings  
Future Integrations (WhatsApp, Email, CRM APIs – Scoped)

*Our Approach*:
- Used Kore.ai’s *Knowledge Graph* to ingest data from Pronix Inc.’s website.
- Trained *custom intents* like `About`, `Contact Info`, `Case Studies`, `Careers`, etc.
- Created *Dialog Tasks* for REST API-based interactions (e.g., "Get company info", "Speak to agent").
- Implemented *Fallback & Agent Transfer* for unanswered queries (Kore default agent panel).
- Partially configured *Voice Agent SIP settings* (SIP handoff supported).
- Recorded interactions and captured *screenshots & demo video* for the final showcase.

*Future Scope*:
- Full SIP integration with real phone call handoff.
- CRM connection via APIs for personalized interaction.
- WhatsApp / Instagram integration for omnichannel support.
- Improved analytics dashboard (user stats, failed queries, etc.)
