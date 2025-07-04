# AI-Powered Lead Welcome Email Automation

This project automates the process of sending personalized welcome emails to new leads using:

- Google Forms and Sheets for lead collection and storage
- n8n for automating the workflow
- OpenRouter (Meta-LLaMA) to generate email content
- Gmail to send the final email

# How It Works

1. A lead submits their information through a Google Form.
2. The data is stored in a connected Google Sheet.
3. The n8n workflow is manually triggered.
4. Lead details are sent to OpenRouter, which generates a welcome email.
5. The email is sent automatically through Gmail.
6. The generated email can optionally be saved back to the sheet.

# Files Included

- `lead_automation.json` – The exported n8n workflow
- `README.md` – This documentation file
- `image.png` – Screenshot of the workflow (for reference)

# Use Case

Useful for educators, small business owners, or service providers who want to automate the welcome email process without coding.

# Status

Fully working with manual trigger mode. Can also be expanded to support real-time automation using Google Apps Script and webhook integration.
GForms tested with: https://forms.gle/ysMTuMR7SsZz5LuD7
