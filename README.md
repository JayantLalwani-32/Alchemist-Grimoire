# 🧪 Alchemist's Grand Grimoire

> A modern, secure, and context-aware wellness application designed to help users maintain perfect medication adherence through intelligent scheduling, AI assistance, and multi-channel reminders.

---

## 🌟 Overview

**Alchemist’s Grand Grimoire** transforms how users manage their health and medication routines.  
By combining **intelligent reminders**, **AI-driven insights**, and **cross-platform synchronization**, it ensures no dose is ever forgotten — and every user’s wellness data is protected with the utmost privacy.

---

## 🧩 Problem Statement

Most people struggle with:
- Forgetting to take medications on time.
- Managing complex schedules across multiple prescriptions.
- Tracking missed doses and long-term adherence.
- Lack of intelligent, context-aware systems to assist daily wellness.

**Alchemist’s Grand Grimoire** solves this by **centralizing medication data**, **automating reminders**, and **providing smart analytics** — all while maintaining security and privacy by design.

---

## 🎯 Core Functionality

### 🧱 Basic Features
- **Dynamic Scheduling:**  
  Create detailed medication schedules with name, dosage, time, and frequency.
  
- **Flexible Alerts:**  
  Receive reminders via Browser Push, Email, or SMS (future integration) with custom pre-alerts (5 min, 15 min, 1 hr, etc.).
  
- **Adherence Logging:**  
  Track taken, missed, or skipped doses in a simple, visual log.
  
- **Secure Authentication:**  
  Two-Factor Authentication (2FA) using Email OTP for enhanced login protection.
  
- **Full Account Control:**  
  Users can securely delete all their associated data (schedules, logs, keys, etc.) at any time.

---

### ⚙️ Advanced Features
- **📊 Data Visualization Dashboard:**  
  Beautiful charts showing adherence rates, trends, and missed doses.

- **⏰ Dynamic Reminder Timing:**  
  Choose custom alert windows (e.g., “Remind me 30 min before dose”).

- **📅 Google Calendar Sync:**  
  Automatically sync medication schedules to your Google Calendar.

- **🤖 AI Chatbot Health Assistant:**  
  Ask questions like “What pills do I need to take today?” or “Did I miss any dose yesterday?”

- **🔁 Dynamic Snooze & Pause:**  
  Instantly snooze reminders for custom durations (5, 15, 30 minutes) or pause indefinitely.

---

## 🤖 AI & Technical Capabilities

- **Gemini AI Integration:**  
  Context-aware chatbot grounded in the user’s medication schedule and dose history.  
  Can also answer general health queries using Google Search grounding.

- **Secure Web Push (VAPID):**  
  Backend uses encrypted VAPID keys to send reliable browser push notifications — even when the app is closed.

- **Stateful Dose Rescheduling:**  
  Dynamic backend logic ensures snoozed doses are rescheduled correctly, maintaining accurate adherence data.

- **Cascading Deletion (MongoDB):**  
  Deleting a user automatically removes all associated schedules and logs for complete privacy.

---

## 🎨 User Experience

- **🖤 Dark/Mystical UI:**  
  A unique “grimoire-inspired” theme for immersive yet comfortable viewing.
  
- **📱 Fully Responsive:**  
  Works seamlessly across mobile, tablet, and desktop.

- **⚡ Fast State Management:**  
  Powered by **Zustand** for reliable and scalable state control across the app.

---

## 🧠 Tech Stack

| Category         | Technologies                                         |
|------------------|------------------------------------------------------|
| **Frontend**     | React, Vite, Tailwind CSS, Zustand                  |
| **Backend**      | Node.js, Express.js, MongoDB, Mongoose              |
| **Authentication**| JWT, Email OTP (2FA)                               |
| **Notifications**| Web Push (VAPID), Node-Cron                          |
| **AI**           | Gemini API (context-aware responses)                 |
| **Integrations** | Google Calendar API                                  |
| **Deployment**   | Render / Vercel (or your preferred host)             |

---

## 🚀 Setup & Installation

### Prerequisites
- Node.js (v18+)
- MongoDB instance
- Environment variables configured in `.env`

### 🧭 Steps
```bash
# Clone the repository
git clone https://github.com/TechBhaskar05/Webster2025.git

# Navigate to the project folder
cd Webster2025

# Install dependencies
npm install

# Create .env file (refer .env.example or instructions for keys)

# Run the development server
npm run dev
