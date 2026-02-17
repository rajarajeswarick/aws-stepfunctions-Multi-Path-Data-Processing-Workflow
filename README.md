# aws-stepfunctions-Multi-Path-Data-Processing-Workflow
Multi Path Data Processing Workflow

Use Case - Routes execution dynamically based on request type.

Architecture Flow

Start
Choice State → Choose execution path

Path A: Call external HTTPS API
Analyze document with Textract

Path B:
Retrieve data via Lambda
Trigger AWS Glue job
End

Services Used

AWS Step Functions
AWS Lambda
Amazon API (HTTP integration)
Amazon Textract
AWS Glue

<img width="481" height="367" alt="image" src="https://github.com/user-attachments/assets/a2f1cf1e-cf90-4c2c-9fa4-c8a5fead8f29" />

