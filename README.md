# AI News Agent

This is an n8n-powered automation that curates the latest AI news from multiple RSS feeds, filters for relevance, summarizes them using Gemini 2.5 Pro, and sends a formatted WhatsApp/email update daily.

## 🔧 Tech Stack
- n8n (Visual Automation)
- Google Gemini 2.5 Pro (for summarization)
- RSS Feeds (OpenAI, MIT Tech Review, TechCrunch, etc.)
- Gmail API (for sending emails)

## ⚙️ Features
- Daily trigger at 9 AM
- Fetches from 6 AI-focused RSS feeds
- Filters by date and AI keywords (regex-based)
- Removes duplicates
- Limits to top 20 most recent items
- Sends WhatsApp/email-friendly summary
- Fully customizable (feeds, keywords, timing)

## 📦 Setup
1. Clone this repo
2. Import `My workflow.json` into your n8n instance
3. Add Gmail + Gemini API credentials
4. Test + enable the workflow

## 📧 Output Format (WhatsApp-Friendly)
AI NEWS DIGEST - 2025-08-07

📢 MAJOR UPDATES
• OpenAI: GPT-5 preview live
• Meta: Llama 3.1 open-source

🔬 RESEARCH
• MIT: New logic benchmark beats GPT-4
• DeepMind: Protein folding upgrade

💰 FUNDING
• Anthropic: $4B Amazon deal


## 🧠 Tips
- You can switch Gemini with GPT-4 for higher quality.
- Add Slack, Telegram, or WhatsApp delivery easily.
- Expand to 10+ RSS feeds with minor tweaks.
