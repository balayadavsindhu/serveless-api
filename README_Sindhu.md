# Serverless Contact API (AWS)

This project builds a serverless REST API using:
- **API Gateway**
- **AWS Lambda**
- **DynamoDB**

## Features
- POST endpoint `/data`
- Stores contact form data into DynamoDB
- Fully serverless architecture

## Lambda Function

See `index.js` for the AWS Lambda code that receives POST requests and writes to DynamoDB.

## Sample Request (cURL)

```bash
curl -X POST https://6hxy6g1nr8.execute-api.ap-south-1.amazonaws.com/data   -H "Content-Type: application/json"   -d '{ "name": "Sindhu", "email": "balayadavsindhu@gmail.com", "message": "Hello" }'
```
