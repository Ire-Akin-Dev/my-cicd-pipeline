\# Serverless Order System (AWS)



A production-style \*\*serverless backend\*\* built on AWS that processes customer orders through a REST API.



This project demonstrates how to design and implement a scalable, event-driven backend without managing servers.



---



\## 🏗️ Architecture



\- \*\*Amazon API Gateway (HTTP API)\*\* – Public REST endpoint

\- \*\*AWS Lambda (Python 3.11)\*\* – Backend business logic

\- \*\*Amazon DynamoDB\*\* – NoSQL data storage

\- \*\*AWS IAM\*\* – Secure service permissions



---



\## 🔄 Request Flow



Client → API Gateway → Lambda → DynamoDB



---



\## ✨ Features



\- Create customer orders via HTTP POST

\- Automatically generated UUID-based order IDs

\- Fully serverless and auto-scaling

\- No server or infrastructure management required



---



\## 📦 Example API Request



```http

POST /orders

Content-Type: application/json



{

&nbsp; "customerName": "Jane Doe",

&nbsp; "product": "Notebook",

&nbsp; "quantity": 2

}

Author: Irewole Akinsanya









