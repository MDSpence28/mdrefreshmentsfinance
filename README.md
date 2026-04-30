# MD Refreshments Vending Machine Tracker

A fully serverless web application built with AWS to manage sales reports and inventory for my vending machine business.

## Live Demo
[https://www.mdrefreshmentsfinance.com/](https://www.mdrefreshmentsfinance.com/)

## Screenshots

### 1. Main Upload Page
![Upload Page](screenshot-upload.png)

### 2. Sales Analytics Dashboard
![Sales Analytics Dashboard](screenshot-dashboard.png)

### 3. Inventory Tracker (Improved)
![Inventory Tracker](screenshot-inventory.png)

## Features
- Upload and parse PayRange CSV sales reports
- Sales analytics dashboard with bar chart visualization (Chart.js)
- Inventory tracker with GPS timestamp logging
- Improved Recent Restocks section with collapsible list grouped by date
- Clean, mobile-friendly UI with red branding matching company logo
- Fully serverless architecture

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript, Chart.js
- **Hosting**: Amazon S3 + CloudFront (HTTPS + custom domain)
- **Backend**: AWS Lambda (Python 3.11)
- **API**: API Gateway HTTP API
- **Database**: Amazon DynamoDB (2 tables)

## What I Learned
- Built and deployed a complete serverless application from scratch
- Handled CSV file uploads and data processing in Lambda
- Managed CORS configuration and API Gateway routing
- Worked with DynamoDB data types and best practices
- Added client-side geolocation for GPS tracking
- Improved user experience with dynamic forms and collapsible sections

## Future Improvements
- QR code scanning for machines
- Stock level calculations and low-stock alerts
- Photo upload with Amazon Rekognition

---

Built with ❤️ for MD Refreshments vending business.
