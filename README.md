# 📧 Cold Email Automation Workflow with n8n + Brevo

This repository contains a complete cold email automation setup using [n8n](https://n8n.io/) and **Brevo (formerly Sendinblue)**. The goal is to help companies send cold emails **safely and effectively** without getting blocked or flagged as spam.

---

## 🧰 What's Included

| File Name                                 | Purpose                                                 |
|------------------------------------------|---------------------------------------------------------|
| `finalbrevon8n.json`                     | Exported n8n workflow with all nodes configured         |
| `n8n installation.pdf`                   | Step-by-step guide to install n8n using Node.js         |
| `n8n workflow using the brevo crm.pdf`   | Complete walkthrough of building and running the cold email workflow using Brevo |
| `README.md`                              | You’re reading it – project overview and instructions   |

---

## 🚀 What This Workflow Does

- Accepts lead data (name, email, LinkedIn URL) via webhook
- Parses the input and appends it to a Google Sheet
- Sends cold emails **one-by-one** using the Brevo email API
- Adds a delay between emails to avoid spam filters
- Designed for **safe cold outreach** at scale

---

## 💡 Why Use This?

- ✅ Prevent getting flagged as spam
- ✅ Easy setup with Google Sheets + Brevo
- ✅ Fully automated and repeatable
- ✅ Based on real-world cold email best practices

---

## 🛠️ How to Use

1. 📥 **Install n8n locally**  
   Refer to `n8n installation.pdf` for installation using Node.js

2. ⚙️ **Set up the workflow**  
   Follow `n8n workflow using the brevo crm.pdf` to:
   - Import the JSON file into n8n
   - Configure your Brevo API key
   - Set Google Sheets credentials
   - Customize your email copy

3. 🧪 **Test and go live**  
   Activate the workflow and send leads via webhook to automate the cold email process.

---

## 🔐 Requirements

- n8n installed locally (or in the cloud)
- Brevo API key
- Google Sheets access with OAuth2 credentials

---

## 👤 Author

**Abhiram Yadav**  
Software Developer  
📧 abhiramoffice7@gmail.com


---

## ⚠️ Disclaimer

This project is built for ethical business use. Ensure you comply with applicable email laws (e.g., CAN-SPAM, GDPR). Avoid unsolicited spam.

