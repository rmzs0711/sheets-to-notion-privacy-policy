# Sheet to Notion

A Chrome extension that exports Google Sheets data directly to Notion pages as tables or databases.

## Features

- Export any Google Sheet to Notion with one click
- Choose between Table or Database format
- Automatic column type detection (text, numbers, dates, checkboxes)
- Secure Google OAuth authentication
- Works with any Notion workspace

## Installation

Install from the [Chrome Web Store](https://chrome.google.com/webstore/detail/sheet-to-notion) (coming soon)

## How It Works

1. Connect your Google account
2. Add your Notion integration token ([how to get one](#how-to-create-a-notion-integration-token))
3. Select a destination page in Notion
4. Open any Google Sheet and click Export

## How to Create a Notion Integration Token

To connect the extension to your Notion workspace, you need to create an integration:

### Step 1: Create an Integration

1. Go to [notion.so/my-integrations](https://www.notion.so/my-integrations)
2. Click **"+ New integration"**
3. Give it a name (e.g., "Sheet to Notion")
4. Select the workspace you want to use
5. Click **"Submit"**

### Step 2: Copy the Integration Token

1. After creating the integration, you'll see an **"Internal Integration Secret"**
2. Click **"Show"** then **"Copy"**
3. Paste this token into the extension when prompted

### Step 3: Connect Integration to Your Pages

**Important:** Notion integrations don't have access to any pages by default. You must explicitly share pages with your integration:

1. Open the Notion page where you want to export sheets
2. Click the **"..."** menu in the top-right corner
3. Scroll down and click **"+ Add connections"**
4. Search for your integration name and select it
5. Click **"Confirm"**

Now the extension can create tables and databases on that page.

## Privacy

We take your privacy seriously. Read our [Privacy Policy](https://rmzs0711.github.io/sheets-to-notion-privacy-policy/).

**Key points:**
- All data processing happens locally in your browser
- We don't collect or store any personal data
- We only request read-only access to your spreadsheets

## Support

If you encounter any issues, please [open an issue](https://github.com/rmzs0711/sheets-to-notion-privacy-policy/issues) on this repository.
