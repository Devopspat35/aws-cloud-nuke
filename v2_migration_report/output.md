# AWS SDKv2 Migration Progress

The table below outlines the progress of the `AWS SDK` migration as detailed in [#745](https://github.com/gruntwork-io/cloud-nuke/issues/745).
run `go generate ./...` to refresh this report.


| Resource Name                    | Migrated           |
|----------------------------------|--------------------|
| accessanalyzer                   | :white_check_mark: |
| acm                              | :white_check_mark: |
| acmpca                           | :white_check_mark: |
| ami                              | :white_check_mark: |
| apigateway                       | :white_check_mark: |
| apigatewayv2                     | :white_check_mark: |
| app-runner-service               | :white_check_mark: |
| asg                              | :white_check_mark: |
| backup-vault                     | :white_check_mark: |
| cloudtrail                       | :white_check_mark: |
| cloudwatch-alarm                 | :white_check_mark: |
| cloudwatch-dashboard             | :white_check_mark: |
| cloudwatch-loggroup              | :white_check_mark: |
| codedeploy-application           | :white_check_mark: |
| config-recorders                 | :white_check_mark: |
| config-rules                     | :white_check_mark: |
| data-sync-location               | :white_check_mark: |
| data-sync-task                   | :white_check_mark: |
| dynamodb                         | :white_check_mark: |
| ebs                              | :white_check_mark: |
| ec2                              |                    |
| ec2-dedicated-hosts              |                    |
| ec2-endpoint                     |                    |
| ec2-keypairs                     |                    |
| ec2-placement-groups             |                    |
| ec2-subnet                       |                    |
| ec2_dhcp_option                  |                    |
| ecr                              | :white_check_mark: |
| ecscluster                       | :white_check_mark: |
| ecsserv                          | :white_check_mark: |
| efs                              | :white_check_mark: |
| egress-only-internet-gateway     |                    |
| eip                              | :white_check_mark: |
| ekscluster                       | :white_check_mark: |
| elastic-beanstalk                | :white_check_mark: |
| elasticache                      | :white_check_mark: |
| elasticacheParameterGroups       | :white_check_mark: |
| elasticacheSubnetGroups          | :white_check_mark: |
| elb                              | :white_check_mark: |
| elbv2                            | :white_check_mark: |
| event-bridge                     | :white_check_mark: |
| event-bridge-archive             | :white_check_mark: |
| event-bridge-rule                | :white_check_mark: |
| event-bridge-schedule            | :white_check_mark: |
| event-bridge-schedule-group      | :white_check_mark: |
| guardduty                        | :white_check_mark: |
| iam                              |                    |
| iam-group                        |                    |
| iam-policy                       |                    |
| iam-role                         |                    |
| iam-service-linked-role          |                    |
| internet-gateway                 |                    |
| ipam                             |                    |
| ipam-byoasn                      |                    |
| ipam-custom-allocation           |                    |
| ipam-pool                        |                    |
| ipam-resource-discovery          |                    |
| ipam-scope                       |                    |
| kinesis-firehose                 |                    |
| kinesis-stream                   |                    |
| kmscustomerkeys                  |                    |
| lambda                           |                    |
| lambda_layer                     |                    |
| lc                               |                    |
| lt                               |                    |
| macie-member                     |                    |
| managed-prometheus               | :white_check_mark: |
| msk-cluster                      |                    |
| nat-gateway                      |                    |
| network-acl                      |                    |
| network-firewall                 |                    |
| network-firewall-policy          |                    |
| network-firewall-resource-policy |                    |
| network-firewall-rule-group      |                    |
| network-firewall-tls-config      |                    |
| network-interface                |                    |
| oidcprovider                     |                    |
| opensearchdomain                 |                    |
| rds                              |                    |
| rds-cluster                      |                    |
| rds-global-cluster               |                    |
| rds-global-cluster-membership    |                    |
| rds-parameter-group              |                    |
| rds-proxy                        |                    |
| rds-snapshot                     |                    |
| rds-subnet-group                 |                    |
| redshift                         |                    |
| route53-cidr-collection          |                    |
| route53-hosted-zone              |                    |
| route53-traffic-policy           |                    |
| s3                               |                    |
| s3-ap                            |                    |
| s3-mrap                          |                    |
| s3-olap                          |                    |
| sagemaker-notebook-smni          |                    |
| secretsmanager                   |                    |
| security-group                   |                    |
| security-hub                     | :white_check_mark: |
| ses-configuration-set            | :white_check_mark: |
| ses-email-template               | :white_check_mark: |
| ses-identity                     | :white_check_mark: |
| ses-receipt-filter               | :white_check_mark: |
| ses-receipt-rule-set             | :white_check_mark: |
| snap                             |                    |
| snstopic                         | :white_check_mark: |
| sqs                              | :white_check_mark: |
| transit-gateway                  | :white_check_mark: |
| transit-gateway-attachment       | :white_check_mark: |
| transit-gateway-route-table      |                    |
| vpc                              |                    |
| vpc-lattice-service              | :white_check_mark: |
| vpc-lattice-service-network      | :white_check_mark: |
| vpc-lattice-target-group         | :white_check_mark: |
