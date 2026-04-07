AWS-Config-Setup-Lab

This lab provides a step-by-step guide on how to enable and configure AWS Config using the AWS Management Console.
AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources,
providing a detailed inventory and configuration history for compliance and security analysis.

 Architecture Components
 
*AWS Config: The primary service for recording resource configurations.

*Amazon S3: Used as a delivery channel to store configuration history and snapshots.

*Amazon SNS (Optional): Used to stream configuration change notifications.

*IAM Role: Grants AWS Config permission to record data and access S3/SNS.

