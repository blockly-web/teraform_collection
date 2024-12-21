# Terraform Blockly Extension

This repository contains Terraform infrastructure blocks for the [Blockly Web Experiment](https://github.com/blockly-web/blockly_experiment) project, providing visual programming capabilities for infrastructure as code.

Live Demo: [https://blockcode.web.app/#/](https://blockcode.web.app/#/)

## Overview

This extension adds Terraform infrastructure blocks to the Blockly visual programming environment, allowing users to create AWS infrastructure using a drag-and-drop interface. The blocks are organized in three complexity levels:

1. **Basic Infrastructure**
   - VPC configuration
   - Subnet management
   - Internet Gateway
   - Route Tables
   - Basic Security Groups

2. **Advanced Infrastructure**
   - EC2 Launch Templates
   - Auto Scaling Groups
   - Application Load Balancer
   - Target Groups
   - Health Checks

3. **Complex Infrastructure**
   - RDS Database
   - S3 Storage
   - CloudWatch Monitoring
   - Private Networking
   - Enhanced Security

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/blockly-web/blockly_experiment
   ```

2. Navigate to the Terraform blocks directory:
   ```bash
   cd terraform_blocks
   ```

3. Import the blocks into your Blockly workspace using the provided XML definitions.

## Block Categories

### Network Blocks
- VPC Creation
- Subnet Management
- Internet Gateway
- Route Tables
- Security Groups

### Compute Blocks
- EC2 Instances
- Auto Scaling
- Load Balancers
- Launch Templates

### Database Blocks
- RDS Instance
- Subnet Groups
- Security Configuration

### Storage Blocks
- S3 Buckets
- Bucket Versioning
- Encryption Settings

### Monitoring Blocks
- CloudWatch Dashboards
- Metric Alarms
- Resource Monitoring

## Usage Examples

1. **Basic VPC Setup**
   - Drag the VPC block
   - Configure CIDR range
   - Add subnets
   - Connect to Internet Gateway

2. **Web Application Infrastructure**
   - Set up VPC and networking
   - Configure Auto Scaling Group
   - Add Load Balancer
   - Set up target groups

3. **Full Stack Application**
   - Complete networking setup
   - Configure compute resources
   - Add RDS database
   - Set up monitoring

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please:
1. Check the [Issues](https://github.com/blockly-web/blockly_experiment/issues) section
2. Visit the [live demo](https://blockcode.web.app/#/) for examples
3. Refer to the [Terraform documentation](https://www.terraform.io/docs) for underlying concepts
