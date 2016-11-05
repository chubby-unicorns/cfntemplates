# cfntemplates
_A collection of generic templates I use for testing CloudFormation. This may include yaml and json templates and perhaps even some [cfndsl](https://github.com/stevenjack/cfndsl) snippets._

### EC2withCloudWatchLogs.json:
From this Snippet in the AWS CloudFormation User Guide:

* _[Amazon CloudWatch Logs Template Snippets](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/quickref-cloudwatchlogs.html)_

My version has been mofidied to be deployed in an _existing_ VPC and subnet. This is required if, like me, you don't have default VPCs in any account/region.
