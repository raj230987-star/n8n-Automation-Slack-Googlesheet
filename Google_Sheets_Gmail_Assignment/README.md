
# Google Sheets to Gmail Automation

## CAIE Course Program - Assignment 9
learn. build. operate

## Project Overview

An automated n8n workflow that retrieves student
course status data from Google Sheets, generates
a structured HTML email report using JavaScript,
and sends it through Gmail.

## Workflow

Manual Trigger
    ↓
Google Sheets - Get Rows
    ↓
Code Node - Generate Email Report
    ↓
Gmail - Send Message

## Technologies Used

- n8n (Self-hosted on Hostinger VPS)
- Google Sheets
- Gmail
- JavaScript
- HTML
- Google OAuth2

## Key Features

- Automatic Google Sheets data retrieval
- Dynamic email subject and body generation
- Student course status summary
- Colour-coded HTML report
- Consolidated email delivery
- Zero AI token consumption

## Execution Results

| Parameter | Result |
|---|---|
| Total Students | 5 |
| Completed | 2 |
| In Progress | 2 |
| Pending | 1 |
| Email Delivery | Successful |

## How to Run

1. Import the workflow JSON into n8n.
2. Configure Google Sheets credentials.
3. Select the spreadsheet and worksheet.
4. Configure Gmail credentials.
5. Enter the recipient email address.
6. Execute the workflow.

## Author

Rajesh B

CAIE Course Program - Assignment 9
