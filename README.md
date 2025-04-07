unzip the 7z file 
for further information you will get a readme file inside the extracted file
the extracted file should be arranged in this manner 
upi-fraud-detection/
│----routes/
!------admin_routes.py
!------auth_routes.py
!------scan_routes.py
├── app.py
├── requirements.txt
├── templates/
│   ├── index.html
│   ├── scan.html
│   └── ...
├── static/
│   └── styles.css
├── firebase-message-sw.js
└── README.md
# UPI Fraud Detection

A Flask app to detect UPI frauds and phishing links.

## Features
- Scan for UPI and URL-based fraud
- Admin dashboard to view reports
- Firebase push notifications
- Authentication system

## How to run locally
1. Install dependencies: `pip install -r requirements.txt`
2. Run with: `python app.py`
