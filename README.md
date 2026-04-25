IndiaMart Lead Automation

Automatically captures, deduplicates, and logs IndiaMart leads to Google Sheets — with instant Telegram alerts and a GPT-4o-mini AI chatbot. Built entirely with n8n. Zero custom backend.


⚡ What It Does
PipelineFunction🔄 Lead SyncFetches leads every 3 hours, deduplicates by ID, saves new ones to Google Sheets📲 Telegram AlertsInstantly notifies sales team with lead name, email, phone & message🤖 AI ChatbotGPT-4o-mini bot answers team queries via Telegram with conversation memory

🛠️ Built With
n8n · Google Sheets API · Telegram Bot API · OpenAI GPT-4o-mini · LangChain

🔧 Setup

Import indiamart-lead-automation.json into n8n
Add credentials — Google Sheets OAuth2, Telegram Bot token, OpenAI API key
Set your IndiaMart webhook URL, Sheet ID, and Telegram Chat ID
Activate ✅


💡 Key Highlights

No duplicate leads — checks every lead ID before saving
Instant notifications — Telegram alert fires the moment a new lead is captured
AI with memory — chatbot remembers last 10 messages per user for natural conversations
100% no-code — built visually in n8n, no backend or servers needed
