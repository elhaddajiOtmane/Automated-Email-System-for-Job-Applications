


# Python Email Automation Script

## Overview

This Python script automates the process of sending emails for job applications. It reads recipient details from a CSV file and sends personalized emails with attached resumes.

## Features

- Personalized email content based on CSV data.
- Attachment support for resumes.
- Secure handling of email credentials using environment variables.

## Requirements

- Python 3.x
- `smtplib`, `csv`, `email.mime` (all part of Python standard library)
- `python-dotenv`: To install, run `pip install python-dotenv`

## Installation

1. Clone this repository or download the script.
2. Install `python-dotenv` using pip:

   ```bash
   pip install python-dotenv
   ```

## Configuration

1. Create a `.env` file in the same directory as your script with the following content:

   ```plaintext
   EMAIL='your_email@gmail.com'
   PASSWORD='your_password'
   ```

   Replace the values with your actual email and password.

2. Update the `job_contacts.csv` file with the details of your recipients.

3. Modify the script to point to the correct path of your resume in the attachment section.

## Usage

Run the script using Python:

```bash
python main.py
```

Ensure that the SMTP server settings match your email provider's requirements.

 ## Credits

This script was created by [Otmane El Haddaji](https://github.com/elhaddajiOtmane).


## License

[This script under GPL license  ]

