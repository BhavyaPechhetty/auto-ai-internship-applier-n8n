# Auto AI Internship Applier using n8n 🤖

## Overview

An AI-powered automation workflow that helps automate the internship application process.

When a new internship opportunity is added to Google Sheets, the workflow uses Google Gemini AI to generate a personalized application email and automatically sends it to the hiring manager through Gmail.

## Workflow

![Workflow](workflow.png)

## Features

- Automatically triggers when a new internship is added
- Reads internship details from Google Sheets
- Generates personalized emails using Gemini AI
- Formats AI response into structured output
- Sends emails automatically using Gmail

## Tech Stack

- n8n
- Google Gemini AI
- Google Sheets API
- Gmail API
- AI Workflow Automation

## How It Works

1. Add internship details to Google Sheet
2. Google Sheets Trigger starts workflow
3. Gemini AI creates a customized email
4. Structured Output Parser separates:
   - Receiver email
   - Subject
   - Email body
5. Gmail sends the application automatically

## Challenges Faced

- Setting up Google OAuth credentials
- Handling API authentication
- Configuring Gemini AI output format
- Connecting multiple services in n8n

## Future Improvements

- Add job scraping automation
- Add resume customization using AI
- Track application status automatically

## Note

Do not upload API keys or personal credentials.
