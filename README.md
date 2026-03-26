# AI Lead Generation Automation (n8n)

## Overview
This project automates lead generation using GitHub data and AI.
It identifies potential leads, generates personalized outreach messages using AI, and sends them directly to Discord.

## Features

*  Fetch GitHub user data via API
*  Filter high-value leads
*  Generate AI-powered personalized messages
*  Send automated alerts to Discord
*  End-to-end workflow automation using n8n

##  Tech Stack

* n8n (Workflow Automation)
* OpenAI API (AI message generation)
* GitHub API (Data source)
* Discord Webhooks (Notifications)

##  Project Structure

* `workflow.json` → n8n workflow file
* `README.md` → Project documentation

---

##  How It Works

1. Fetch GitHub users using API
2. Filter relevant/high-value profiles
3. Generate personalized outreach message using AI
4. Merge user data with AI output
5. Send formatted message to Discord channel


##  Setup Instructions

### 1️⃣ Import Workflow

* Open n8n
* Import `workflow.json`

### 2️⃣ Add Credentials

* Add GitHub API token
* Add OpenAI API key
* Add Discord webhook URL

⚠️ Do NOT include tokens in the JSON file (security best practice)

##  Output Example

🔥 High Value Lead Found!

👤 Name: John Doe
🏢 Company: Google
🧠 Bio: Software Engineer

💡 AI Pitch:
Personalized outreach message generated using AI...

##  Use Case

This project is useful for:

* Recruiters
* Sales teams
* Startups
* Business development professionals

##  Future Improvements

* Save leads to Google Sheets
* Add email automation
* Implement lead scoring system
* Build dashboard for analytics

---

##  Author

Jnaneshwari N

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
