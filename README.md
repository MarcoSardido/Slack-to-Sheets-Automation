
# SmartInvoice Flow: Slack-to-Sheets Automation

## 📄 Description

This workflow streamlines invoice management by automatically processing PDFs or images of invoices sent in Slack. Once an invoice is uploaded, the system extracts key details (e.g., items, prices, totals) using OCR and AI, then logs the data into a structured Google Sheet. Finally, a summary of the parsed data is sent back to Slack for confirmation—eliminating manual entry and reducing errors.

--

## Features
- **Slack Integration**: Automatically receives invoice PDFs or images directly from Slack channels or direct messages.
- **OCR Processing**: Extracts text and invoice details from uploaded invoice files using Optical Character Recognition.
- **AI Parsing**: Uses AI to intelligently identify and categorize invoice items, prices, totals, and other key information.
- **Google Sheets Logging**: Saves extracted invoice data into a preformatted Google Sheet for easy tracking and reporting.
- **Automated Confirmation**: Sends a summary of the extracted invoice details back to Slack for user review and confirmation.
- **Error Reduction**: Minimizes manual data entry errors by automating the entire invoice capture process.
- **Scalable & Customizable**: Easily adaptable to different invoice formats and Slack workflows.

---

## 🛠 Usage

### Prerequisites
- Slack workspace with access to relevant channels.
- Google account with access to Google Sheets API.


### Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/MarcoSardido/Slack-to-Sheets-Automation.git
    ```

2. **Set up n8n**

- Install n8n locally or use n8n Cloud

- Follow the official guide: https://docs.n8n.io/hosting/

3. **Import the Workflow**

- Log in to your n8n dashboard

- Click on Import Workflow

- Upload the provided .json workflow file in this repository

4. **Configure API Credentials**

- Slack: Configure Slack app and get your Bot Token and Signing Secret.

- Google Sheets: Set up Google Sheets API credentials and share your target sheet with the service account email.

---
## 📸 Screenshots

![App Screenshot](https://res.cloudinary.com/deiymcwio/image/upload/v1752486229/snapshot_fs3sad.png)

---## Tags
`automation` `Slack` `Google Sheets` `OCR` `AI` `invoice-processing` `workflow` `data-extraction`