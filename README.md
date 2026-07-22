# 🤖 AI Automation Blueprint

This is the central documentation for my generic, multi-channel AI Customer Support ecosystem.

## 🏗️ System Architecture
- **Chatbot Brain**: Voiceflow (Handles website chat and logic)
- **Automation Glue**: Make.com (Connects Email, WhatsApp, and Webhooks)
- **Voice Agent**: Vapi.ai (Planned for Phase 2)

## 🧠 Core System Prompt (The "Cheat Sheet")
The AI is instructed to act as a helpful, industry-specific assistant. It strictly avoids answering out-of-scope questions (like weather or time) and redirects users politely.

**Example Prompt Rule:**
> "If a user asks about the time, weather, or anything not related to the specific business, reply exactly with: 'I'm the helpful assistant for [Business Name]! I can help you with [Industry Tasks]. For other things, I recommend checking your phone!'"

## 🔗 Live Demos
- **Website Chatbot Demo**: https://creator.voiceflow.com/share/6a6148e175275148d99280a5/environment/main/draft 
- **WhatsApp Demo**: [Coming Soon]

## 📈 Next Steps
- [ ] Connect Make.com to Gmail for auto-responses.
- [ ] Integrate WhatsApp Business API.
