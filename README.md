# 🎯 FinTech Competitor Intelligence System

> Automated competitive intelligence pipeline 
> for FinTech startups — monitors news 24/7, 
> analyzes with AI, updates Notion dashboard 
> automatically.

![Status](https://img.shields.io/badge/Status-Live-brightgreen)
![Cost](https://img.shields.io/badge/Cost-$0%2Fday-blue)
![Built With](https://img.shields.io/badge/Built%20With-n8n-orange)

---

## 📌 What Problem Does This Solve?

Most FinTech startups waste 3-4 hours per week 
manually tracking what competitors are doing.

This system does it automatically:
- Monitors 5 target companies 24/7
- Analyzes news with AI
- Categorizes by importance
- Sends weekly executive brief
- Updates Notion dashboard in real time

**Cost of manual research:** $25-40/hour × 
3 hours/week = ~$4,000/year

**Cost of this system:** ~$0/day

---

## 🏗️ System Architecture

           FINTECH INTELLIGENCE          
               SYSTEM v1.0                


WORKFLOW 1 — Daily News Monitor

⏰ Schedule Trigger (8:00 AM daily)
│
▼
📰 NewsAPI — Fetch latest news
(15 articles, 5 target companies)
│
▼
⚙️  Extract & Clean Articles
│
▼
🔍 Filter — Last 24 hours only
│
▼
🤖 Groq AI Analysis
• Company identification
• Category classification
• Importance rating
• 2-sentence summary
│
▼
📊 Notion Database — Auto-save
(structured, searchable)
WORKFLOW 2 — Weekly Digest
─────────────────────────────────
⏰ Schedule Trigger (Monday 9:00 AM)
│
▼
📥 Notion — Fetch last 7 days data
│
▼
⚙️  Format & Sort by Importance
│
▼
🤖 Groq AI — Generate executive brief
│
▼
📧 Gmail — Send weekly digest email
---

## 🛠️ Tech Stack

| Tool | Purpose | Cost |
|------|---------|------|
| n8n Cloud | Automation backbone | Free tier |
| NewsAPI | News data source | Free (100 req/day) |
| Groq AI | Intelligence analysis | Free |
| Notion | Dashboard + storage | Free |
| Gmail | Weekly digest delivery | Free |

**Total running cost: $0/day**

---

## 📊 What Gets Monitored

Target companies (customizable):
- Stripe
- Coinbase
- Revolut
- NayaPay
- Wise

Intelligence categories:
- 💰 Pricing changes
- 🚀 New features
- 💵 Funding rounds
- 👥 Leadership changes
- 🤝 Partnerships
- 📰 General news

---

## ⚡ Key Features

**Daily Automation**
- Runs at 8:00 AM automatically
- Zero manual intervention
- Processes 15 articles per run
- Takes ~47 seconds total

**AI Analysis Layer**
- Powered by Groq Llama 3.3 70B
- Identifies company automatically
- Classifies into 6 categories
- Rates importance (High/Med/Low)
- Generates 2-sentence analysis

**Notion Dashboard**
- Real-time updates
- 5 different views
- Filter by company/category
- Search across all intelligence

**Weekly Email Brief**
- Every Monday 9:00 AM
- AI-generated executive summary
- Top developments highlighted
- Market implications included

---

## 📈 Results After 3 Days
Articles Processed: 45+
Intelligence Items Saved: 38
High Priority Items: 8
Average Processing Time: 47 seconds
Manual Hours Saved: ~2 hours
API Cost: $0.00
---

## 🚀 How to Set This Up

### Prerequisites
n8n Cloud account (free)
NewsAPI account (free)
Groq API account (free)
Notion account (free)
Gmail account
### Step 1: Get API Keys
NewsAPI:  newsapi.org → Get API Key
Groq:     console.groq.com → API Keys
Notion:   notion.so/my-integrations

### Step 2: Import Workflows
[Workflow JSON files coming soon]

### Step 3: Configure Credentials
n8n → Credentials → Add:

Groq API Key
Notion Token
Gmail OAuth

### Step 4: Set Target Companies
Edit NewsAPI URL query parameter:
q=Company1+OR+Company2+OR+Company3

### Step 5: Activate
Both workflows → Toggle Active
System runs automatically

---

## 📁 Project Structure
fintech-intelligence-system/
│
├── README.md
├── workflows/
│   ├── daily-news-monitor.json
│   └── weekly-digest.json
├── docs/
│   ├── setup-guide.md
│   └── architecture.md
└── screenshots/
├── n8n-workflow.png
├── notion-dashboard.png
└── email-digest.png

---

## 🗓️ Build Log

| Day | What Was Built |
|-----|---------------|
| Day 1 | Accounts setup, Notion database |
| Day 2 | Daily news monitor workflow |
| Day 3 | Weekly digest + Notion dashboard |
| Day 4 | Documentation + GitHub setup |

---

## 🔮 Roadmap

- [ ] Add LinkedIn post monitoring
- [ ] Slack notification integration  
- [ ] Competitor pricing tracker
- [ ] Mobile dashboard (Notion mobile)
- [ ] Custom scoring algorithm

---

## 👤 Built By

**MOEEZ KHAN**
FinTech Growth & AI Automation Specialist

- LinkedIn: https://www.linkedin.com/in/moeezkhan1/
- Email: kmoeez649@gmail.com

---

*Built as part of a public FinTech 
portfolio project — documented daily 
on LinkedIn.*
