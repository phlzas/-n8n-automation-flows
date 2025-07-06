# 🚀 n8n Automation Flows – Omar Rashdan

This repo contains some of my best automation workflows built with [n8n](https://n8n.io). These workflows solve real problems using APIs, AI, and powerful integrations.

Each `.json` file is a ready-to-import n8n workflow. Below are the highlights.

---

## 🧠 1. SEO Content Optimizer (with Google Search Console)

**Goal:** Improve underperforming web pages using AI recommendations.

**Key Features:**
- Connects to Google Search Console & BigQuery
- Analyzes content performance
- Suggests new titles, meta descriptions, and sections
- Generates reports (Google Sheets + HTML)

**Tech Used:** GSC API, Google Drive, OpenAI (GPT-4o), Google Sheets

---

## 📲 2. Social Media Uploader (Instagram + TikTok)

**Goal:** Auto-upload videos from Google Drive to TikTok and Instagram with AI-generated captions.

**Key Features:**
- Google Drive trigger for new videos
- Uses Whisper to transcribe audio
- Generates catchy captions
- Posts videos automatically
- Sends Telegram alerts on error

**Tech Used:** upload-post.com API, OpenAI, Telegram API

---

## 🛠️ 3. AI-Powered GitHub Code Reviewer

**Goal:** Automate pull request reviews with LLMs.

**Key Features:**
- Detects new PRs
- Fetches code diffs
- Uses Mistral-7B via OpenRouter for code suggestions
- Posts review comments on GitHub

**Tech Used:** GitHub API, OpenRouter (LangChain), LangChain Agent

---

## 💡 More flows coming soon...

Feel free to fork or reach out if you’d like to collaborate or hire!

**👨‍💻 Omar Rashdan**  
LinkedIn: [linkedin.com/in/omarrshdan](https://www.linkedin.com/in/omar-ahmed-0875aa2b4/)  
GitHub: [github.com/omarrshdan](https://github.com/phlzas) 
