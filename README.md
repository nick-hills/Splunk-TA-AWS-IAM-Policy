# Splunk-TA-AWS-IAM-Policy

This policy document contains all the necessary baseline permissions for the Splunk AWS TA to perform API data & metadata collection and to allow the inputs editor to browse available S3 bukets and SQS queues.

For Inputs that rely on S3 or SQS (or both) you will need to add specific buckets at the bottom. 3 Placeholders are provided for your billing, cloudtrail and config buckets.
