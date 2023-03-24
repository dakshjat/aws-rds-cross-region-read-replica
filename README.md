# Amazon RDS for Oracle Cross-Region Read Replica

Use the AWS CloudFormation template to create Amazon RDS for Oracle cross-region read replica.


___
![Architecture Diagrams](https://user-images.githubusercontent.com/47545538/227514661-2e59cd5c-feb1-4d72-92f8-0809b6b2ce98.jpg)

___

To create an AWS CloudFormation stack, you can use the following options:

**#1.** From the AWS console, create an AWS CloudFormation stack with new resources, specify the template, and enter appropriate parameters.

**#2** Use the below AWS CLI command to create an AWS CloudFormation stack with a parameter file:

* `aws cloudformation deploy --stack-name aws-dms-oracle --template-file aws-rds-cross-region-read-replica.yaml --parameter-overrides file://parameters.json`
___

For more information on Amazon RDS DB instance read replicas, visit [Working with DB instance read replicas](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_ReadRepl.html).

For more information on Amazon RDS for Oracle read replicas, visit [Working with read replicas for Amazon RDS for Oracle](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/oracle-read-replicas.html).