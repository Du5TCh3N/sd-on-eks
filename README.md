# Guidance for asynchronous inference with Stable Diffusion-Web UI on AWS

Implementing a fast scaling and low cost Stable Diffusion inference solution with serverless and containers on AWS

Stable Diffusion is a popular open source project for generating images using Gen AI. Building a scalable and cost efficient inference solution is a common challenge AWS customers facing. This project shows how to use serverless and container services to build an end-to-end low cost and fast scaling asyncronous image generation architecture. This repo contains the sample code and CDK deployment scripts, helping you to deploy this solution in a few steps.

## Features

- Asyncronous API and Serverless Event-Driven Architecture
- Image Generation with Stable Diffusion Web UI on Amazon EKS
- Automatic queue length based scaling with KEDA
- Automatic provisioning ec2 instances with Karpenter
- Scaling up new inference nodes within 2 minutes
- Saving up to 70% with GPU spot instances

## Documentations

Check out our [live docs]! (https://aws-samples.github.io/stable-diffusion-on-eks/en/)

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under MIT-0 License. See the [LICENSE](LICENSE) file.
