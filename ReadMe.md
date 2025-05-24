# AWS AMI Resources

Welcome to the AWS AMI Resources repository! This repository contains essential resources, scripts, and templates to help you get the most out of our AWS Marketplace AMIs.

## Overview

This repository serves as a centralized hub for all supplementary materials related to our AWS Marketplace AMI offerings. Here you'll find CloudFormation templates, installation scripts, and documentation to help you quickly deploy and configure our solutions in your AWS environment.

## Repository Structure

```
aws-ami-resources/
├── prometheus-grafana/          # Resources for Prometheus & Grafana AMI
│   ├── cloudformation/         # CloudFormation templates
│   └── scripts/               # Installation and setup scripts
└── [future-ami-resources]/    # Additional AMI resources (as we expand)
```

## Available AMI Resources

### 1. Prometheus & Grafana Monitoring Solution

A pre-configured monitoring stack for AWS environments that provides:
- Automated EC2 instance discovery and monitoring
- Pre-built Grafana dashboards
- CloudFormation templates for IAM setup
- Node Exporter installation scripts

For detailed instructions, see [prometheus-grafana/README.md](prometheus-grafana/README.md).

### 2. [Future AMI Name] (Coming Soon)

Additional AMI resources will be added here as our marketplace portfolio expands.

## Prerequisites

- AWS CLI installed and configured
- Appropriate AWS permissions for resource creation
- Active subscription to the corresponding AWS Marketplace AMI

## Getting Started

1. **Clone this repository**:
   ```bash
   git clone https://github.com/[your-org]/aws-ami-resources.git
   cd aws-ami-resources
   ```

2. **Navigate to the specific AMI resource directory**:
   ```bash
   cd [ami-name]  # e.g., prometheus-grafana
   ```

3. **Follow the README** in the specific AMI directory for detailed setup instructions.

## Support

### Documentation
Each AMI resource directory contains:
- Detailed README with setup instructions
- CloudFormation template documentation
- Script usage guides
- Troubleshooting information

### Getting Help
- **Technical Issues**: Please open an issue in this repository
- **AMI-specific questions**: Contact through AWS Marketplace support
- **Feature requests**: Submit via GitHub issues with the "enhancement" label

## Contributing

We welcome contributions to improve these resources! Please:
1. Fork this repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## Security

- Never commit sensitive information (credentials, keys, etc.)
- All scripts are provided as-is - review before running in production
- Report security issues privately to [security@your-org.com]

## License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) file for details.

## Updates

This repository is regularly updated with:
- New AMI resources as they become available
- Updated scripts and templates
- Bug fixes and improvements
- Additional documentation

⭐ **Star this repository** to stay updated with the latest resources!

---

**Note**: Always refer to the specific AMI documentation in AWS Marketplace for the most up-to-date information about features and requirements.
