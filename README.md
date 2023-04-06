# Rust AWS Lambda EFS File Lister

This Rust mini-project aims to create an AWS Lambda function that lists all the files in an Amazon Elastic File System (EFS) volume. The Lambda function is written in Rust and leverages the AWS SDK for Rust to interact with the EFS.

## Overview

The primary goal of this project is to provide a serverless solution to list all the files in an EFS volume. The Lambda function can be triggered by various AWS services like API Gateway, S3, or CloudWatch Events, making it a flexible and easily integrable solution.

## Prerequisites

To run and deploy this project, you'll need the following:

1. Rust installed on your system.
2. AWS CLI installed and configured with your AWS credentials.
3. Docker installed (for building the Lambda function package).
4. An existing EFS volume in your AWS account.


## Usage
1. cargo lambda invoke --remote --data-ascii '{"name": "<your_name>"}' --output-format json efs-lister { "files": "\n\n/mnt/efs/foo.txt", "msg": "<your_msg>", "req_id": "<your_id>" }
## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you encounter any problems or have suggestions for improvements.




## References

* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
