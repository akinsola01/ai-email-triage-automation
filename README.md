![Demo](assets/ai_email_triage_demo.gif)

# AI Email Triage Automation

An AI-powered workflow built with n8n that automatically reads customer inquiries, extracts actionable information using GPT, and sends structured summaries to Slack while acknowledging the customer by email.

## Problem

Businesses receive customer inquiries through multiple channels, making it difficult to identify urgent requests and respond quickly.

## Solution

This workflow:

- Reads incoming emails
- Filters irrelevant messages
- Uses GPT to extract important information
- Sends a structured Slack notification
- Sends an acknowledgment email
- Logs all requests

## Tech Stack

- n8n
- OpenAI GPT-4.1
- Gmail
- Slack
- Google Sheets
- Webhooks

## Workflow

![Workflow](assets/ai_triage_architecture.png)


## Full video:
https://www.loom.com/share/88091488d23a4e9f80c772c0505f191a

## Features

- AI classification
- Deadline extraction
- Appointment extraction
- Automatic email reply
- Slack alerts
- Structured outputs
