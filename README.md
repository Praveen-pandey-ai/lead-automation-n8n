## n8n Workflow

The file `n8n/lead_webhook_google_sheets_workflow.json` contains the exported n8n workflow.

### What it does
- Accepts lead data via webhook
- Validates lead fields
- Checks duplicate email in Google Sheets
- Appends new row for unique leads

### How to use
1. Import the JSON into n8n
2. Activate workflow
3. Call webhook-test URL using Postman
4. Verify Google Sheet update
