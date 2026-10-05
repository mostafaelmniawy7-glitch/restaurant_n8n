# restaurant_n8n # 
AI Restaurant Bot — Telegram & Google Sheets

An intelligent restaurant chatbot built with n8n that handles customer orders, answers menu questions, and manages everything through Google Sheets.

## Features

- Telegram Bot — customers chat directly via Telegram
- AI Agent — GPT-powered with intent classification
- Knowledge Base — answers menu, prices, and FAQ questions
- Order Management — creates and tracks orders automatically
- Google Sheets Backend — orders stored and managed in real-time
- Human Handoff — escalates complex queries
- Intent Router — classifies requests (order / question / general)

## Tech Stack

- n8n — Workflow automation
- OpenAI — GPT for classification and responses
- Telegram Bot API — Customer interface
- Google Sheets — Orders & business data
- Vector Store — Knowledge base for RAG

## How It Works

1. Customer sends message on Telegram
2. AI classifies intent (order / question / general)
3. Request routes to the right prompt
4. Agent uses tools to answer or create order
5. Data saved to Google Sheets
6. Reply sent back to Telegram

## Screenshots

- Telegram conversation
- n8n workflow
- Google Sheets dashboard

## Use Cases

- Restaurants & cafés
- Cloud kitchens
- Food delivery services
- Any order-based business
