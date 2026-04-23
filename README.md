# AI_news Automation

An automated AI news summarization workflow built with n8n.

## Features
- Runs daily at 9:00 AM
- Fetches latest AI news from Google News RSS
- Summarizes top headlines using Groq LLM
- Sends digest to Gmail automatically

## Stack
- n8n
- Groq API
- Gmail API
- RSS Feed

## Workflow Steps
Schedule Trigger -> RSS Feed -> Build Prompt -> Groq Summary -> Gmail Send

## Model Used
llama3-8b-8192

## Setup
1. Import newsflow.JSON into n8n
2. Add Groq API key
3. Connect Gmail credentials
4. Activate workflow

## Use Cases
- Daily AI learning
- Productivity digest
- Founder/researcher updates
- Email automation
