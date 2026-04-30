# MD Refreshments Vending Machine Tracker

A serverless web application built with AWS to track sales and inventory for my vending machines.

## Features
- Upload and parse PayRange CSV sales reports
- Sales analytics dashboard with Chart.js visualization
- Inventory tracker with GPS timestamp logging
- Grouped recent restocks view

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript, Chart.js
- **Hosting**: S3 + CloudFront (HTTPS + custom domain)
- **API**: API Gateway HTTP API
- **Backend**: Python 3.11 Lambda
- **Database**: DynamoDB (two tables: sales + inventory)

## Live Site
https://www.mdrefreshmentsfinance.com/

## Setup
This is a static site + serverless backend. No local server required.

## Future Improvements
- QR code scanning for machines
- Photo upload with Amazon Rekognition
- Stock level calculations and low-stock alerts
- Structured error logging