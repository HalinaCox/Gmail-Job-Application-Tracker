# Gmail Job Application Tracker

An AI-powered Make.com automation that extracts job application data from your Gmail and organizes it into a Google Sheet.

## 🚀 Quick Start (No Coding Required)

### One-Click Import

**[👉 Click here to import directly into Make.com](https://us2.make.com/public/shared-scenario/3qrplab0bio/integration-gmail-open-ai-chat-gpt-sora)**

This link will take you straight to Make.com with the workflow ready to import. Just click "Import" and follow the setup steps below!

---

## How It Works

1. **Monitors your Gmail inbox** for incoming emails
2. **Uses OpenAI's ChatGPT** to intelligently parse email content
3. **Extracts key information:**
   - Application date
   - Company name
   - Job role/title
   - Application status
   - Pipeline stage
   - Recruiter/contact name
   - Contact email
4. **Automatically populates a Google Sheet** with the extracted data

---

## Setup Instructions

### Prerequisites (All Free)

- Gmail account
- Google account (usually same login)
- Make.com account (free tier) — [Sign up here](https://make.com)
- OpenAI account (free tier) — [Sign up here](https://platform.openai.com)

### Step-by-Step Setup

**Step 1: Import the Workflow**
1. Click the link above to go to Make.com
2. Click "Import" when prompted
3. You're done with this step!

**Step 2: Connect Your Gmail**
1. In Make.com, you'll see a red warning on the Gmail module (that's normal)
2. Click on the Gmail module
3. Click "Add" next to the connection
4. A popup will ask for Gmail access — click "Allow"
5. Done!

**Step 3: Create Your Google Sheet**
1. Go to [Google Drive](https://drive.google.com)
2. Click "New" → "Google Sheets"
3. Name it "Job Applications Tracker" (or whatever you like)
4. Create these column headers:
   - A: Date
   - B: Company
   - C: Role
   - D: Status
   - E: Stage
   - F: Contact Name
   - G: Contact Email

**Step 4: Connect Google Sheets in Make.com**
1. Go back to Make.com
2. Click on the **Google Sheets module** (the last one)
3. Click "Add" for the connection
4. Click "Allow" when Google asks
5. Select your "Job Applications Tracker" sheet
6. Make sure "Table contains headers" is set to YES

**Step 5: Connect OpenAI**
1. Go to [OpenAI API Keys](https://platform.openai.com/account/api-keys)
2. Click "Create new secret key"
3. Copy the key
4. Go back to Make.com
5. Find the **OpenAI module**
6. Click "Add" for connection
7. Paste your API key
8. Done!

**Step 6: Test It**
1. Click the "Run once" button in Make.com
2. Send yourself a test email (subject line with job company name)
3. Wait 30 seconds
4. Check your Google Sheet — your data should appear!

---

## File Structure

- `Gmail-Job-Application-Tracker-Agent.json` — The complete Make.com workflow (ready to import)
- `SETUP_GUIDE.md` — Detailed setup guide with screenshots
- `README.md` — This file

---

## Status

🚧 **In Development** — This workflow is functional but still being refined. The ChatGPT extraction logic is being continuously optimized for better accuracy. 

### Known Limitations
- Works best with standard job application emails
- May need manual adjustment for highly formatted emails
- OpenAI API costs ~$0.001-0.01 per email processed

---

## Technologies Used

- **Make.com** — Automation/workflow platform
- **Gmail API** — Email access
- **OpenAI API (ChatGPT)** — Intelligent data extraction
- **Google Sheets API** — Spreadsheet integration

---

## Cost

- **Make.com** — Free tier includes 1,000 operations/month (plenty for job hunting)
- **OpenAI API** — ~$0.001-0.01 per email (pay-as-you-go, very cheap)
- **Gmail/Google Sheets** — Free

**Total monthly cost**: $0-2 for most users

---

## Next Steps to Refine

- [ ] Fine-tune ChatGPT prompts for even better extraction accuracy
- [ ] Add filtering for specific date ranges
- [ ] Add error notifications
- [ ] Support for additional job board emails
- [ ] Auto-labeling of emails once processed

---

## Troubleshooting

**Q: I got an error when importing**
A: Make sure you're logged into Make.com before clicking the import link

**Q: My Google Sheet isn't updating**
A: Check that your column headers match exactly (Date, Company, Role, Status, Stage, Contact Name, Contact Email)

**Q: OpenAI is costing too much**
A: Reduce the email limit in the Gmail module from 10 to 5, or run it manually instead of on a schedule

**Q: The data extraction isn't accurate**
A: This is currently being refined! Feel free to open an Issue with examples of emails that didn't extract correctly

---

## Contributing

Found a bug? Have a suggestion? Open an Issue or submit a Pull Request!

---

## License

This project is open source and available to everyone.

---

## Questions?

- Check the Setup Guide for detailed walkthroughs
- Review Make.com's documentation: [make.com/docs](https://make.com/docs)
- Open an Issue on this GitHub repo

Happy job hunting! 🎯
