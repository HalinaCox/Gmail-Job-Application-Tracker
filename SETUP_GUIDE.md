# Setup Guide (No Coding Required!)

This guide walks you through everything step-by-step. No technical experience needed.

## What You'll Need (Free accounts)

1. A Gmail account (you already have this)
2. A Google account (same login usually)
3. An OpenAI account (free tier available at openai.com)
4. A Make.com account (free tier available at make.com)

## Step 1: Create a Make.com Account

1. Go to [make.com](https://make.com)
2. Click **"Sign up"** (top right)
3. Use your email to create an account
4. Verify your email
5. You're in!

## Step 2: Import the Workflow

1. In Make.com, click **"Create a new scenario"**
2. Look for **"Templates"** or **"Import"** button
3. Choose **"Upload JSON"**
4. Upload the `Gmail-Job-Application-Tracker-Agent.json` file from this GitHub repo
5. Click **"Import"**

## Step 3: Connect Your Gmail

1. You'll see a red warning on the Gmail module (that's normal)
2. Click on the Gmail module
3. Click **"Add"** next to the connection
4. A popup will ask for Gmail access
5. Click **"Allow"** when Google asks
6. Done!

## Step 4: Connect Your Google Account (for Sheets output)

1. Find the **"Google Sheets"** module (the last one)
2. Click on it
3. Click **"Add"** for the connection
4. Click **"Allow"** when Google asks
5. Create a new Google Sheet (or use an existing one)
6. Copy the Sheet ID and paste it into Make.com
7. Make sure your sheet has these column headers:
   - Date
   - Company
   - Role
   - Status
   - Stage
   - Contact Name
   - Contact Email

## Step 5: Connect OpenAI

1. Go to [openai.com](https://platform.openai.com/account/api-keys)
2. Sign up or log in
3. Click **"API keys"** on the left
4. Click **"Create new secret key"**
5. Copy the key
6. Go back to Make.com
7. Find the OpenAI module
8. Click **"Add"** for connection
9. Paste your API key
10. Done!

## Step 6: Test It

1. Click the **"Run once"** button in Make.com
2. Send yourself a test email (about a job application)
3. Check your Google Sheet — the data should appear!

## Need Help?

- Stuck? Email me or open an Issue on GitHub
- Make.com has great documentation too: [make.com/docs](https://make.com/docs)
