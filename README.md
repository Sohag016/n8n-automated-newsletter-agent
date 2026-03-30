# 🤖 Automated Newsletter Agent (n8n Workflow)

## 🌐 Live Demo

🔗 Temporary Demo Link:  
https://transsolid-tambra-subvitreous.ngrok-free.dev/workflow/fNqlvAaNagXy0cVy

⚠️ Note:
This is a temporary ngrok link. The workflow will only be accessible when the local server is running.

An intelligent workflow built using n8n that automates newsletter form submission handling, data storage, and email notifications using AI.

---

## 🚀 Features

- 📩 Automatically triggers on form submission  
- 🤖 AI-powered response using Google Gemini  
- 📊 Stores user data in Google Sheets  
- ✉️ Sends confirmation email to users  
- ⚡ Fully automated workflow  

---

## 🧠 Workflow Overview

This workflow performs the following steps:

1. **Form Submission Trigger**
   - Captures user input when a form is submitted

2. **AI Agent Processing**
   - Uses Google Gemini Chat Model to process and generate intelligent responses

3. **Data Storage**
   - Saves user data into Google Sheets database

4. **Email Notification**
   - Sends a confirmation email to the user via Gmail

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation  
- **Google Gemini AI** – AI processing  
- **Google Sheets API** – Data storage  
- **Gmail API** – Email delivery  

---

## 📂 Project Structure

```
automated-newsletter-agent/
├── workflow.json
├── README.md
└── email-template.html (optional)
```

---

## ⚙️ Setup Instructions

### 1️⃣ Install n8n

```bash
npm install -g n8n
```

### 2️⃣ Start n8n

```bash
n8n
```

Open: http://localhost:5678

---

### 3️⃣ Import Workflow

- Go to n8n Editor  
- Click **Import Workflow**  
- Upload `workflow.json`  

---

### 4️⃣ Configure Credentials

You need to connect:

- Google Account (Sheets + Gmail)
- Google Gemini API (if required)

---

## 📬 Example Use Case

User fills a newsletter form →  
AI processes the data →  
Data stored in Google Sheets →  
Confirmation email sent automatically  

---

## ⚠️ Important Notes

- Do NOT upload credentials to GitHub  
- Use environment variables or n8n credentials manager  
- Keep API keys secure  

---

## 💡 Future Improvements

- Personalization using AI  
- Newsletter content generation  
- Scheduled email campaigns  
- Analytics dashboard  

---

## 👨‍💻 Author

** Md Sohag Hossain**  
CSE Student | ML & AI Enthusiast  

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
