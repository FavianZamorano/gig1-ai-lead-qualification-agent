AI-powered lead qualification agent built with n8n + LLM. Automatically qualifies, prioritizes, and personalizes responses to inbound leads in real time.

# AI Lead Qualification Agent

An automated lead-handling agent built with **n8n** and **Groq (Llama 3.3 70B)** that reads every inbound lead, qualifies it, assesses urgency, and sends a personalized reply — all within seconds, with zero manual triage.

## Demo

https://github.com/user-attachments/assets/62f500bd-3be5-467d-ac2f-21f884033ff3

## What it does

1. A lead submits a form on the business's website
2. An AI model reads the message and determines:
   - Whether the lead is genuine or low-quality/spam
   - How urgent it is
   - A personalized email reply referencing their specific inquiry
3. The lead is saved to a spreadsheet, the personalized reply is sent automatically via email, and the business owner is notified in real time via Telegram with an AI-generated summary

## Why AI, not just automation

Most lead-capture workflows just store form data and send a generic "thanks, we'll be in touch" email. This agent actually reads and understands each lead — a vague, low-effort inquiry gets flagged differently than a serious, budget-ready one, and every reply is written specifically for that person's message.





