# S3 Event Notifications Lambda Function

AWS Lambda function is designed to be triggered by events from an S3 bucket. When an event occurs in the S3 bucket (such as object creation, deletion, etc.), this Lambda function will be invoked. It then extracts information about the event (such as the event name, bucket name, and object key) from the event data and sends a notification about this event to an SNS topic. Once a message is published to a topic, SNS delivers copies of the message to each subscribed endpoint. This ensures that all subscribed endpoints receive the notification.








