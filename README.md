# Attendance Marking System 

A serverless attendance marking application built using AWS Lambda, API Gateway, DynamoDB, and S3.

## Features
- Accepts student ID as input
- AWS Lambda validates and stores attendance status
- API Gateway exposes a secure HTTP endpoint
- DynamoDB stores attendance records
- Frontend hosted on AWS S3

## AWS Architecture
- S3 → Frontend (HTML/CSS/JS)
- API Gateway → REST endpoint
- Lambda → Backend logic (Node/Python)
- DynamoDB → Data store

## Learning Objectives
- Understanding serverless computing
- IAM roles & permissions
- Connecting frontend to backend using API Gateway
- Using DynamoDB for NoSQL storage

## How It Works
1. User enters ID → Clicks Present/Absent  
2. JS sends a request to API Gateway  
3. API triggers Lambda  
4. Lambda writes data to DynamoDB  
5. Response shown on frontend  

