# AI Photo Search & Album

This is a serverless photo album application built on AWS. It allows users to upload photos which are automatically analyzed and tagged using Machine Learning (AWS Rekognition). Users can then search for photos using natural language queries (e.g., "show me photos of dogs").

## Features
- **Smart Upload:** Automatically tags photos with labels (e.g., "Beach", "Person") upon upload.
- **Natural Language Search:** Search for photos using keywords or sentences.
- **Custom Labels:** Supports adding custom tags during upload.
- **Voice Search:** Integrated microphone support for voice queries.

## Architecture
- **Frontend:** S3 Static Website Hosting (HTML/CSS/JS).
- **API:** AWS API Gateway (REST).
- **Backend:** AWS Lambda (Python).
- **Search Engine:** AWS OpenSearch Service.
- **AI/ML:** AWS Rekognition (Image Analysis) & Amazon Lex (Query Disambiguation).
- **Infrastructure as Code:** AWS CloudFormation.
- **CI/CD:** AWS CodePipeline.

## Deployment
This project is deployed using AWS CloudFormation. The `cloudformation.yaml` template provisions all necessary resources including S3 buckets, Lambda functions, and API Gateway.
