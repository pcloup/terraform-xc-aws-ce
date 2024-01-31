## Overview

Terraform templates to create F5XC AWS cloud CE.

### Topologies

| Name                                    | Description                                                                  |
|-----------------------------------------|------------------------------------------------------------------------------|
| Single Node Single NIC new VPC / subnet | [Description](/examples/single_node_single_nic_new_vpc_new_subnet/readme.md) |
| Single Node Multi NIC new VPC / subnet  |                                                                              |

## Requirements

| Name                                                                                     | Version  |
|------------------------------------------------------------------------------------------|----------|
| <a name="requirement_terraform"></a> [terraform](https://github.com/hashicorp/terraform) | >= 1.3.0 |

## Installation

- Git binary (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- Terraform binary (https://developer.hashicorp.com/terraform/install?product_intent=terraform)
- F5 XC Credentials (https://docs.cloud.f5.com/docs/how-to/user-mgmt/credentials)
    * API Certificate
    * API Token
- SSH public key
    * ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

## Usage

- Clone this repo with: `git clone --recurse-submodules https://github.com/f5devcentral/f5-xc-aws-ce`
- Enter repository directory with: `cd f5-xc-aws-ce`
- Several example directories are available. Change to the example directory that is to be deployed
  with `cd examples/<example_dir_name>`
- Follow usage instruction in examples readme file `cd examples/<example_dir_name>/README.md`

## Support

For support, please open a GitHub issue. Note, the code in this repository is community supported and is not supported
by F5 Networks. For a complete list of supported projects please reference [SUPPORT.md](SUPPORT.md).

## Community Code of Conduct

Please refer to the [F5 DevCentral Community Code of Conduct](code_of_conduct.md).

## License

[Apache License 2.0](LICENSE)

## Copyright

Copyright 2014-2020 F5 Networks Inc.

### F5 Networks Contributor License Agreement

Before you start contributing to any project sponsored by F5 Networks, Inc. (F5) on GitHub, you will need to sign a
Contributor License Agreement (CLA).

If you are signing as an individual, we recommend that you talk to your employer (if applicable) before signing the CLA
since some employment agreements may have restrictions on your contributions to other projects.
Otherwise by submitting a CLA you represent that you are legally entitled to grant the licenses recited therein.

If your employer has rights to intellectual property that you create, such as your contributions, you represent that you
have received permission to make contributions on behalf of that employer, that your employer has waived such rights for
your contributions, or that your employer has executed a separate CLA with F5.

If you are signing on behalf of a company, you represent that you are legally entitled to grant the license recited
therein.
You represent further that each employee of the entity that submits contributions is authorized to submit such
contributions on behalf of the entity pursuant to the CLA.
