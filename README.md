# AI Email Triage & Digest System

## 🚀 Overview

This project automates email management using AI and workflow automation.

It classifies incoming emails into categories and generates a daily digest to improve productivity.

---

## 🔧 Features

* Classifies emails into:

  * Urgent
  * Follow-up
  * FYI
* Automatically applies Gmail labels
* Generates daily summary email
* Fully automated using n8n workflows

---

## 🛠 Tech Stack

* n8n (workflow automation)
* Gmail API (Google Cloud OAuth)
* Google Gemini API (AI classification)

---

## 🧠 How it Works

1. New email arrives in Gmail
2. n8n triggers workflow
3. Gemini API classifies email
4. Label applied automatically
5. Emails grouped into categories
6. Daily digest sent via email

---

## 📸 Screenshots

![alt text](<Screenshot 2026-04-26 131301.png>)
![alt text](<Screenshot 2026-04-26 131347.png>)
---

## 📂 Setup Instructions

1. Import the provided JSON workflow into n8n
2. Configure Gmail credentials
3. Add Gemini API key
4. Activate workflow

---

## 💡 Learnings

* Prompt engineering for AI accuracy
* Workflow automation using n8n
* API integration (Gmail + Gemini)

---

## 🔮 Future Improvements

* Hybrid rule-based + AI classification
* Slack/WhatsApp notifications
* Priority scoring system
