# Personalized Email Automation Tool

## Project Overview
This is a Python-based email automation tool designed to send personalized emails to a list of recipients using Gmail's SMTP server. The project demonstrates email automation, data processing, and professional Python scripting.

## Features
- Read recipient data from a CSV file
- Personalize emails with recipient names
- Randomize email sending order
- Robust error handling for email sending
- Timestamp logging of email sends

## Prerequisites
- Python 3.7+
- pandas library
- Gmail account with App Password enabled

## Setup and Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/personalized-email-automation-tool.git
   ```

2. Install required dependencies:
   ```
   pip install pandas
   ```

3. Create an `email_list.csv` with the following columns:
   - `name`: Recipient's name
   - `email`: Recipient's email address
   - `subject`: Email subject line
   - `message`: Email body content

4. Set up Gmail App Password:
   - Go to your Google Account
   - Navigate to Security > 2-Step Verification
   - Create an App Password for this script
   - Replace `SENDER_PASSWORD` with the generated app password

## Usage
```bash
python email_automation.py
```

## Security Notes
- Never commit sensitive information like passwords to version control
- Use environment variables or secure credential management for sensitive data

## Disclaimer
This tool is for educational and professional demonstration purposes. Ensure compliance with email communication laws and regulations.

## License
[Choose an appropriate open-source license, e.g., MIT License]



## Contact
Deep Patel - deeppatel291001@gmail.com
