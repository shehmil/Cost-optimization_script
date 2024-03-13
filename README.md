# Cost-optimization-script
This AWS Lambda function automates the cleanup of EBS snapshots by identifying and deleting snapshots that are either orphaned (not attached to any volume) or associated with volumes that are not attached to running EC2 instances. This helps in efficient management of AWS resources, especially in environments where snapshot retention and cleanup are critical for cost optimization and resource hygiene. The script utilizes Boto3 to interact with AWS services and includes error handling for robust execution.
![Innovative Solutions](https://github.com/shehmil/Cost-optimization_script)
# Cost-optimization_script
