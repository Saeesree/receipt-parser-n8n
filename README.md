# Receipt Parser - n8n Workflow

Automatically extracts receipt data from Gmail using OpenAI and saves to Google Sheets.

## Flow
Gmail Trigger → OpenAI (GPT-4o-mini) → Code Parser → Google Sheets

## Setup
1. Import the workflow JSON into n8n
2. Configure Gmail OAuth credentials
3. Configure OpenAI API key
4. Configure Google Sheets OAuth credentials
5. Create a Google Sheet with headers: Date, Vendor, Amount, Category, Email Subject

## Tech Stack
- n8n (self-hosted)
- Gmail API
- OpenAI GPT-4o-mini
- Google Sheets API