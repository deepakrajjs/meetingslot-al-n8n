# 📅 MeetingSlot AI using n8n

An automated meeting slot booking system built using N8N. This project helps users schedule meetings easily by handling slot availability, confirmations, and notifications — all without writing code!

---

## 🚀 Features

- 📥 Accepts meeting slot requests via webhook
- 🗓️ Validates available slots from a predefined calendar  
- ✅ Confirms the selected slot automatically
- 📧 Sends email (or message) confirmation to participants
- 🔄 Easily customizable for Google Calendar, Notion, or Telegram

---

## 🛠️ Built With

- **n8n** (low-code workflow automation)
- **Webhook** (to receive slot requests)
- **Email/Telegram/Notion** (optional integrations)
- **JSON** file or custom logic for available slots

---

## 🔧 Setup Instructions

1. Clone this repo or import the workflow `.json` file into your n8n instance.
2. Set up your credentials in n8n (Email, Telegram, etc.).
3. Configure the `Webhook` node with your own public URL (via n8n cloud or tunnel like `ngrok`).
4. Modify the **available slots logic** to match your preferences.
5. Activate the workflow and test it!



---

## 💡 Ideas to Improve

- Add Google Calendar integration
- Add a front-end form to select slots
- Auto-rescheduling logic if slots are taken
- WhatsApp / SMS notifications

---

## 🙌 Credits

Created by Deepak raj 
Feel free to contribute or customize this project for your own use!

---

## 📄 License

This project is open source under the (LICENSE).
