

# Setting Up Infrastructure on AWS using Terraform

### Project Description

* In this project, we aim to establish a robust and scalable infrastructure on Amazon Web Services (AWS) by leveraging Terraform, an Infrastructure as Code (IaC) tool.
*  AWS component involved: VPC, ASG, Route 53, ELB, EC2, S3, Internet Gateway.
    
* These components will be provisioned and Configured using Terraform, an infrastructure-as-code (IaC) tool, to ensure Efficient and Reproducible infrastructure Deployment.

### Architecture

![Alt text](https://github.com/asimar007/Dark-Mode/blob/main/Terraform.png?raw=true)

### Prerequisites

To follow this tutorial you will need:

-   [An AWS account](https://aws.amazon.com/free/)
-   The  [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)  installed
-   Your AWS credentials are configured locally.

1.  With your account created and the CLI installed to configure the AWS CLI.

```
aws configure
```
### Providers

The  provider  block configures the named provider, in my case  `aws`, which is responsible for creating and managing resources. A provider is a plugin that Terraform uses to translate the API interactions with the service. A provider is responsible for understanding API interactions and exposing resources. Because Terraform can interact with any API, you can represent almost any infrastructure type as a resource in Terraform.

