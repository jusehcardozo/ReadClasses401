Jose Cardozo
02/09/2023


What are some of the IoCs that GuardDuty can detect?

Reconnaissance, Instance compromise, Account compromise, Bucket compromise, Malware detection, Container compromise.



What are some of the data sources which GuardDuty can use?

CloudTrail management event logs, CloudTrail S3 data event logs, VPC Flow Logs, DNS query logs, and Amazon EKS audit logs.



How does GuardDuty use access behavior to spot potential malicious activity?

With GuardDuty, EventBridge, and AWS Lambda, you have the flexibility to set up automated remediation actions based on a security finding. For example, you can create a Lambda function to modify your AWS security group rules based on security findings. If you receive a GuardDuty finding indicating one of your EC2 instances is being probed by a known malicious IP, you can address it through an EventBridge rule, initiating a Lambda function to automatically modify your security group rules and restrict access on that port.
