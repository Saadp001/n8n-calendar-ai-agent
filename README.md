# Calendar AI Agent using n8n

This project implements a simple Calendar AI Agent using **n8n**, **OpenAI**, and **Google Calendar**.

The agent understands natural language commands from a chat interface and blocks time slots on Google Calendar automatically.

---

## 🔹 Features
- Chat-based trigger using n8n Chat node
- Natural language understanding using OpenAI
- Automatic event creation in Google Calendar
- Confirmation message sent back to the user

---

## 🔹 Example Commands
- "Set a meeting today at 12"
- "Block my calendar tomorrow at 4 PM"
- "Schedule a call next Monday at 10 AM"

---

## 🔹 Workflow Overview
1. User sends a message via chat
2. OpenAI extracts event details (title, start, end)
3. Parsed data is sent to Google Calendar
4. Event is created and time slot is blocked
5. User receives confirmation via chat

---

## 🔹 Tech Stack
- n8n
- OpenAI
- Google Calendar API

---

## 🔹 Screenshots
Screenshots of the workflow, chat interaction, and calendar event are available in the `screenshots/` folder.

---

## 🔹 Notes
- Default meeting duration is 1 hour if not specified
- Time zone handled via n8n settings

---

## 🔹 Author
Saad Patel
