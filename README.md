CompaintIQ – AI-Based Complaint Classifier

📌 Project Overview

CompaintIQ is an AI-powered complaint management and classification system built using n8n workflow automation.

The system receives complaints through a Telegram bot, uses Google Gemini AI to analyze and classify them, stores complaint details in Google Sheets, sends confirmation messages to students, and sends email notifications through Gmail.

The main aim is to automate complaint handling and make the complaint management process faster and more organized.

🚀 Technologies Used

- n8n: Workflow automation and integration.
- Telegram Bot: Receives complaints from students.
- Google Gemini AI: Analyzes and classifies complaints.
- Google Sheets: Stores complaint records.
- Gmail: Sends email notifications.

⚙️ Workflow Architecture

The workflow consists of the following steps:

1. Telegram Trigger: Receives complaint messages submitted by students through Telegram.
2. Classify Complaint: Processes the complaint using an AI-powered classification node.
3. Gemini Model: Provides AI capabilities to understand and classify complaint messages.
4. Save Complaint: Stores the complaint information in Google Sheets.
5. Confirm to Student: Sends a confirmation message to the student through Telegram.
6. Send a Message: Uses Gmail to send an email notification.

✨ Key Features

- Automated complaint collection through Telegram.
- AI-based complaint classification using Gemini.
- Automated complaint data storage in Google Sheets.
- Instant confirmation messages to students.
- Email notifications through Gmail.
- Reduced manual effort in complaint management.

📂 Project Structure

CompaintIQ/
│
├── CompaintIQ.json
├── README.md
└── workflow-screenshot.png

🛠️ How It Works

The student submits a complaint through the Telegram bot. The n8n workflow automatically receives the message and forwards it to the AI classification node.

Google Gemini analyzes the complaint and generates the classification output. The complaint details are then stored in Google Sheets.

After processing, the student receives a confirmation message through Telegram, and an email notification is sent using Gmail.

🔐 Security

- API keys and authentication credentials are not included in the repository.
- Telegram, Google Gemini and Gmail integrations require valid credentials.
- Users should configure their own credentials before running the workflow.

🎯 Project Objective

To develop an AI-powered automated complaint management system that simplifies complaint submission, classification, storage and notification using AI and workflow automation.

👩‍💻 Developed By

Sakshi Lakade

Third Year – Computer Engineering

Project: CompaintIQ – AI-Based Complaint Classifier
