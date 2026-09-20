# Hospital Booking Automation (n8n)

An AI-powered hospital booking assistant built with n8n, using a single AI Agent (not rigid if/switch logic) to handle the full patient journey — booking through discharge and follow-up.

## Features
- **Channel:** Telegram (patient-facing chat)
- **AI Agent architecture:** Chat Model + Memory + Tools
- **RAG knowledge base:** Pinecone vector store lets the agent answer general hospital FAQs accurately
- **Booking tools:** Google Calendar integration for checking availability and creating appointments
- **Appointment IDs:** every booking generates a unique reference
- **Voice in/out:** patients can send and receive voice messages
- **Current-date awareness:** a dedicated tool keeps the agent's date/time accurate

## Demo
Built for a fictional hospital ("Lekki Grace Hospital") to showcase the system without misrepresenting a real business.

## Stack
n8n · Telegram Bot API · OpenAI · Pinecone · Google Calendar API

## Files
- `workflow.json` — exported n8n workflow, importable directly into your own n8n instance
