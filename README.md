
# 🤖 Dots AI – Smart Email Assistant + Calendar Booker

Dots AI is a smart virtual assistant built with n8n, OpenAI, and Google integrations. It reads user messages, responds like a real assistant, and now books meetings for you automatically.

---

## 🔧 Features

- 💬 Intelligent email composition using OpenAI GPT-4o-mini
- 📩 Auto-replies via Gmail with custom sign-off
- 🧠 Memory buffer to maintain context
- 📅 **New**: Google Calendar integration to auto-book meetings

---

## 📅 Calendar Booking Details

Dots AI understands prompts like:
> “Schedule a 30-minute meeting with Alex next Friday at 2 PM”

It extracts:
- `Start DateTime`
- `End DateTime`
- `Event Title`

And creates a meeting in your Google Calendar.

---

## 🛠️ Tech Stack

- n8n (no-code automation)
- OpenAI GPT-4o-mini
- Gmail OAuth2
- Google Calendar API

---

## 🧠 How It Works

1. Chat message received via webhook
2. Processed through a GPT agent with memory
3. Sends Gmail reply using extracted context
4. Optionally books a calendar event using AI output

---

## ⚙️ Setup Instructions

1. Import the provided `.json` file into your n8n instance
2. Add credentials:
   - OpenAI API Key
   - Gmail OAuth2
   - Google Calendar OAuth2
3. Test it by typing something like:  
   _“Please send an email to John and book a call with him tomorrow at 3 PM.”_

---

## 👤 Built by

Adedotun Adeeko  
Cloud + Automation Enthusiast
