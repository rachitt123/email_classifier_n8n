# email_classifier_n8n
AI-powered email classifier built with n8n and Google Gemini. Automatically classifies emails as Urgent/General/Spam and takes appropriate actions.

# AI Email Classifier & Auto-Responder 🤖📧

An intelligent email automation system built with n8n and Google Gemini AI.

## What it does
- Reads incoming Gmail emails every minute
- Uses Gemini AI to classify emails as Urgent, General, or Spam
- **Urgent** → AI writes a draft reply + sends Telegram alert
- **General** → Auto-replies within seconds
- **Spam** → Logs to Google Sheets, no reply

## Tech Stack
- n8n (workflow automation)
- Google Gemini 2.5 Flash (AI classification)
- Gmail API
- Google Sheets
- Telegram Bot API

## Tools Used
- n8n Cloud
- Google AI Studio (Gemini API)
- Google OAuth2
