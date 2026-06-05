# serverless-aws-employee-management-system

A serverless employee management application built on AWS.  
This project uses **Amazon S3** for frontend hosting, **API Gateway** as the REST API layer, **AWS Lambda** for backend logic, and **Amazon DynamoDB** as the database.

It provides a simple interface to **add** and **view** employee records through a clean web UI.

---

## Architecture

**User → S3 Static Website → API Gateway → Lambda → DynamoDB**

### Optional authentication layer
The architecture can also be extended with **AWS Cognito** for secure user sign-in and access control.

---

## Features

- Add employee records
- View all employee records
- Serverless frontend and backend
- REST API integration
- Fast and scalable NoSQL storage
- Minimal infrastructure management

---

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Hosting:** Amazon S3
- **API Layer:** Amazon API Gateway
- **Backend:** AWS Lambda
- **Database:** Amazon DynamoDB
- **Authentication:** AWS Cognito (optional / future enhancement)

---

## Project Structure

```bash
serverless-aws-employee-management-system/
├── index.html
├── insertEmployeeData.py
├── getEmployees.py
└── README.md
