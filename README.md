# StudyBuddy - Telegram AI Study Friend

StudyBuddy is a Telegram AI bot that explains study concepts in natural Telugu (Guntur style), like a best friend.

## How It Works
Telegram Trigger -> AI Agent (Google Gemini) -> Send Message

## Features
- Explains in 90% natural Telugu (Guntur style) + Technical words in English
- Calls the user by their name
- Short answers in 6-8 lines, like a story
- Gives one small real-life example
- Simple, friendly and motivating tone

## Tech Stack
- n8n - Workflow Automation
- Telegram Bot API - Chat Interface
- Google Gemini - AI Model

## Setup
1. Open n8n and click Import
2. Select the `My_workflow.json` file
3. Connect your Telegram Credentials
4. Connect your Google Gemini API Key
5. Activate the Workflow

## Example
User: What is DBMS?
Bot: DBMS means Database Management System. Let me explain why we need it...

## Author
Pramod Kumar
