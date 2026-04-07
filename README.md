# AI Email Responder

Automatically replies to incoming Gmail emails 
using Groq AI (Llama 3.3) via n8n automation.

## What It Does
- Detects new incoming emails via Gmail Trigger
- Filters out noreply and newsletter emails
- Sends email content to Groq AI
- AI generates a professional reply
- Reply is sent back to sender automatically

## Tools Used
- n8n automation
- Gmail OAuth2
- Groq AI (llama-3.3-70b-versatile)
- IF node for filtering

## How It Works
1. Gmail Trigger detects new email
2. IF node filters unwanted emails
3. Groq AI reads email and writes reply
4. Gmail sends reply back to sender

## Workflow Structure
Gmail Trigger → IF node → Basic LLM Chain → Gmail Send

## Screenshot
<img width="1108" height="438" alt="Screenshot 2026-04-07 064651" src="https://github.com/user-attachments/assets/06c13f69-737a-4cd1-8424-8030d2e32e3c" />
