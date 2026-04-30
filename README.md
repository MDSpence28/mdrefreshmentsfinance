# MD Refreshments Vending Machine Tracker

A fully serverless web application built with AWS to track sales reports and inventory for my vending machines.

## Live Demo
[https://www.mdrefreshmentsfinance.com/](https://www.mdrefreshmentsfinance.com/)

## Features
- Upload and parse PayRange CSV sales reports
- Sales analytics dashboard with bar chart visualization (Chart.js)
- Inventory tracker with GPS timestamp logging and recent restocks view
- Clean, mobile-friendly UI with red branding

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript, Chart.js
- **Hosting**: Amazon S3 + CloudFront (HTTPS + custom domain)
- **API**: API Gateway HTTP API
- **Backend**: AWS Lambda (Python 3.11)
- **Database**: Amazon DynamoDB (two tables: sales + inventory)

## Architecture
Static frontend served from S3 → API Gateway routes requests → Lambda handles business logic and DynamoDB operations.

## What I Learned
- Serverless architecture design
- CORS configuration on API Gateway
- Data type handling with DynamoDB (Decimal vs Float)
- Least-privilege IAM policies
- Path normalization and client-side geolocation

## Future Improvements
- QR code scanning for machines
- Photo upload with Amazon Rekognition
- Stock level calculations and low-stock alerts
- Structured error logging

---

