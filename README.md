# Gmail Job Application Tracker

An AI-powered Make.com automation that extracts job application data from your Gmail and organizes it into a Google Sheet.

## How it works

1. Monitors your Gmail inbox for incoming emails
2. Uses OpenAI's ChatGPT to intelligently parse email content
3. Extracts key information:
   - Application date
   - Company name
   - Job role/title
   - Application status
   - Pipeline stage
   - Recruiter/contact name
   - Contact email
4. Automatically populates a Google Sheet with the extracted data

## Setup

1. Import this workflow into [Make.com](https://make.com)
2. Connect your Gmail account
3. Connect your Google account (for Sheets output)
4. Connect your OpenAI API key
5. Create a Google Sheet with columns: Date, Company, Role, Status, Stage, Contact Name, Contact Email
6. Run the automation

## File

- `Gmail-Job-Application-Tracker-Agent.json` - The complete Make.com workflow

## Next Steps to Refine

- [ ] Fine-tune ChatGPT prompts for better data extraction
- [ ] Add filtering for specific date ranges
- [ ] Add email labels/categorization
- [ ] Add error notifications

## Technologies Used

- Make.com (automation platform)
- Gmail API
- OpenAI API (ChatGPT)
- Google Sheets API
