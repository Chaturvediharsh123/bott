# bot
# 🩸 Blood Donation Chatbot (Botpress)

A smart and interactive chatbot built using **Botpress** to help users find and donate blood, check blood availability in banks, and get notifications for urgent needs.

---

## 📌 Features

- 🏥 Search for available blood types in nearby blood banks  
- 🧑‍🤝‍🧑 Register as a blood donor  
- 📲 Notify users about urgent blood requirements  
- 🔍 FAQs about blood donation  
- 📅 Schedule or get reminders for donation

---

## 🚀 How It Works

This chatbot was developed using [**Botpress**](https://botpress.com), an open-source platform for creating powerful conversational agents.

It includes:
- **Flows** for collecting user data (blood group, contact, location)
- **Tables** for storing donor and request data
- **Conditions and triggers** to handle responses and notifications

---

## 📁 Project Structure

```bash
blood-donation-bot/
├── data/
│   ├── global/
│   └── bots/
│       └── blood-donation/
│           ├── flows/
│           ├── content/
│           └── bot.config.json
├── .gitignore
├── README.md
└── blood-donation.bpz (optional export file)
