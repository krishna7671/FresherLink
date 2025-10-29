# Detailed Setup Guide for FresherLink

This guide provides step-by-step instructions to help you set up the FresherLink application.

## 1. Google Sheets Setup

### 1.1. Create Your Spreadsheet

1.  Go to [Google Sheets](https://sheets.google.com) and create a new spreadsheet.
2.  Rename the spreadsheet to "FresherLink Data".
3.  Create three sheets within the spreadsheet and name them:
    *   `Gigs`
    *   `Freelancers`
    *   `Matches`

### 1.2. Get Your Spreadsheet ID

1.  Open your "FresherLink Data" spreadsheet.
2.  The URL in your browser's address bar will look like this:
    `https://docs.google.com/spreadsheets/d/YOUR_SPREADSHEET_ID/edit`
3.  Copy the `YOUR_SPREADSHEET_ID` part of the URL. This is your spreadsheet ID.

## 2. Make.com Setup

### 2.1. Import the Scenario

1.  Go to [Make.com](https://www.make.com) and create a new scenario.
2.  Click the "More" button in the bottom center of the screen, and then click "Import Blueprint".
3.  Select the `automation/make_scenario.json` file from this repository.

### 2.2. Configure the Google Sheets Modules

1.  In the "Watch New Gig" module, you will be prompted to connect to your Google account.
2.  Once connected, select your "FresherLink Data" spreadsheet and the "Gigs" sheet.
3.  Repeat this process for the "Get Freelancer Data" and "Write Match Result" modules, selecting the "Freelancers" and "Matches" sheets, respectively.
4.  After configuring the Google Sheets modules, Make.com will store a connection ID. You will need to find this in your Make.com account settings under "Connections".

## 3. OpenAI Setup

### 3.1. Get Your OpenAI API Key

1.  Go to [platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys).
2.  Click "Create new secret key".
3.  Copy the key and save it in a safe place.

### 3.2. Configure the OpenAI Module

1.  In the "AI Skill Matching" module in your Make.com scenario, you will be prompted to add an OpenAI connection.
2.  Paste your OpenAI API key when prompted.
3.  Make.com will create a connection and you can find the `YOUR_OPENAI_CONNECTION_ID` in your Make.com account settings under "Connections".
