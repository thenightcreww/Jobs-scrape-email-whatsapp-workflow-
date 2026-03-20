🚀 Job Scraper Automation (n8n Workflow)

⚡ Fully automated system to scrape jobs and send real-time alerts via Email & WhatsApp

🌐 Live Demo

🔗 View Live Project:
👉 https://manpreet1singh2.github.io/Jobs-scrape-email-whatsapp-workflow-/

📌 Overview

This project is an end-to-end automation workflow built using n8n that scrapes job listings (LinkedIn & other sources), processes structured data, and delivers instant notifications via Email and WhatsApp.

It eliminates manual job searching and ensures users never miss relevant opportunities.

✨ Key Features

✅ Automated Job Scraping

Extract jobs from LinkedIn and other platforms

Handles real HTML parsing

✅ Accurate Data Extraction

Job Title

Company Name

Location

Job URL

Job ID

✅ Smart Parsing Engine

Uses real LinkedIn DOM structure

Fixed CSS selectors for accurate results

✅ Real-Time Notifications

📧 Email Alerts

📱 WhatsApp Messages

✅ Scalable Workflow

Easily extendable for multiple job sources

Supports batch processing

🧠 Workflow Architecture
🔧 Core Fix (Important)

The main issue in the workflow was incorrect parsing selectors.

✅ Correct Selectors Used
Field	Selector
Title	h3.base-search-card__title
Company	h4.base-search-card__subtitle > a
Location	span.job-search-card__location
Job Link	a.base-card__full-link
Job ID	data-entity-urn
📂 Project Structure
📦 project-root
 ┣ 📄 workflow.json   # n8n workflow file
 ┣ 📄 README.md
🚀 Setup Instructions
1️⃣ Import Workflow

Open n8n

Click Import

Upload workflow.json

2️⃣ Configure Credentials

📧 Email (SMTP / Gmail API)

📱 WhatsApp API (Twilio recommended)

🌐 HTTP Node (job source URL)

3️⃣ Run Workflow

Click Execute Workflow

✅ Jobs will be scraped and processed

✅ Notifications sent automatically

📊 Output Example
Title	Company	Location
Automation Engineer	Siemens	Pune
AI Engineer	Intuit	Bangalore
QA Engineer	Times of India	Delhi
🔐 Security

No unnecessary data storage

Secure API communication

Can be adapted for self-hosted environments

🧩 Tech Stack

⚙️ n8n (Workflow Automation)

🧠 JavaScript (Parsing Logic)

🌐 HTTP Requests (Scraping)

📧 Gmail API / SMTP

📱 WhatsApp API (Twilio)

🎯 Use Cases

Job alert systems

Recruitment automation

Lead generation pipelines

AI-based job matching systems

🚀 Future Enhancements

🤖 AI-based job recommendation

📊 Dashboard analytics

📩 Auto job apply system

🔔 Telegram / Slack alerts

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

⭐ Support

If you found this useful:
👉 Star this repo
👉 Share with others
👉 Connect for collaboration

👨‍💻 Author

Manpreet Singh
Full Stack & AI Automation Developer

📧 dimplebrar13@gmail.com

🔗 https://github.com/manpreet1singh2

🔥 Built for speed, automation, and real-world impact.
