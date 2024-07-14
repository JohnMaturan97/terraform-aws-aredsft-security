# Terraform AWS Redshift Security Module

This Terraform module provisions AWS security configurations specifically tailored for a Redshift database environment, enhancing security and compliance.

## Features

- **Enhanced Security**: Configures security groups, roles, and policies optimized for Redshift databases.
- **Compliance Ready**: Ensures configurations meet common compliance frameworks requirements.
- **Automation**: Automates the security setup, reducing manual configuration errors and effort.

## Usage

To use this module in your Terraform environment, add the following configuration to your Terraform files:

```hcl
module "aredsft_security" {
  source  = "path/to/module"

  # Variables
  environment = "<your-environment>"
  security_settings = "<specific-settings>"
  ...
}
```

## Requirements

- Terraform 0.13+
- AWS provider 3.0+

## Providers

| Name | Version |
|------|---------|
| aws | ~> 3.0 |

## Inputs

Please refer to `variables.tf` for a detailed description of each variable.

## Outputs

Please refer to `outputs.tf` for details about the outputs that this module provides.

## License

Distributed under the Apache 2.0 License. See `LICENSE` file for more information.

## Authors

- **John Mharlou N. Maturan**
