![Data Exchange logo](adx-logo.png)

## AWS Data Exchange Daily Fantasy Sports Football Lineups Optimizer

[AWS Data Exchange](https://aws.amazon.com/data-exchange/) is a service that makes it easy for millions of AWS customers to securely find, subscribe to, and use third-party data in the cloud. This repository contains an example of how to use data from Stats Perform to optimize your daily fantasy sports football lineups.

![Data Exchange diagram](adx-dfs-diagram.svg)

You can get started using this notebook in 4 easy steps:
1. Subscribe to the Stats Perform data [here](https://aws.amazon.com/marketplace/pp/prodview-tte3yvctdjs7a).
2. Create an Amazon SageMaker Notebook instance [here](https://console.aws.amazon.com/sagemaker/home?region=us-east-1#/notebook-instances). For the development of this notebook, we used an `ml.m5.xlarge`. Note that charges apply.
3. Once your instance has been spun up, click 'Open Jupyter' and upload optimizer.ipynb from this repository.
4. Once uploaded, open optimizer.ipynb and update the variable at the top to point to the S3 bucket you want to use. As long as the IAM role you're using has the permissions listed in the notebook, the code will "just work".

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

