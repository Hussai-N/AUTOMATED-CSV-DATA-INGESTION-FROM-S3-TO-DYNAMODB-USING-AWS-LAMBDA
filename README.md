# Automated CSV Data Ingestion from S3 to DynamoDB using AWS Lambda

## 📌 Project Overview
This project automates the ingestion of **CSV data** from an **S3 bucket** into an **Amazon DynamoDB table** using **AWS Lambda**. Whenever a CSV file is uploaded to S3, a **Lambda function** is triggered to parse the file and insert its contents into DynamoDB.

---

## ⚙️ Technologies Used
- **Amazon S3** (Storage & Event Source)
- **AWS Lambda** (Serverless Compute)
- **DynamoDB** (NoSQL Database)
- **IAM Role** (Permissions for S3 & DynamoDB)
- **Python (boto3)** (Lambda Function Code)
- **CloudWatch** (For logging)

---

## 🚀 Process Flow
1. **CSV file uploaded** to an **S3 bucket**.
2. **S3 Event Notification** triggers the **Lambda function**.
3. **Lambda reads the CSV file**, processes each row, and inserts the data into **DynamoDB**.
4. **CloudWatch Logs** capture execution details.

---

## ✨ Key Features
- **Fully serverless** and **event-driven**.
- **Real-time data ingestion** with zero manual intervention.
- **Scalable & cost-effective** using AWS Lambda.
- **Customizable** for different CSV formats and table structures.
- **Secure IAM Role-based access** (no hard-coded credentials).

---

## 📂 Example Folder Structure
```bash
📁 Project Folder
├── 📄 lambda_function.py  # Lambda logic
├── 📄 sample_data.csv      # Example CSV file
├── 📄 README.md            # This file
