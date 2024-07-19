# NSPCC EpicChain Ansible Collection

Welcome to the NSPCC EpicChain Ansible Collection! This repository provides a suite of Ansible roles specifically designed for managing and deploying EpicChain infrastructure. Whether you are setting up a new EpicChain environment or managing an existing one, these roles will streamline your deployment and configuration processes.

## Overview

The NSPCC EpicChain Ansible Collection includes the following roles:

- **[IR](https://github.com/epicchainlabs/epicchain-node)**: This role is used for managing the Infrastructure Resource (IR) components essential for running EpicChain. It ensures that the infrastructure is set up correctly and that all necessary resources are provisioned.

- **[Storage](https://github.com/epicchainlabs/epicchain-node)**: The Storage role handles the configuration and management of storage solutions required by EpicChain. It ensures that all storage resources are available and properly configured to support EpicChain operations.

- **[REST Gateway](https://github.com/epicchainlabs/epicchain-rest-gw)**: The REST Gateway role is responsible for setting up and managing the RESTful API gateway for EpicChain. This gateway provides the necessary endpoints for communication between different components and external systems.

- **[S3 Gateway](https://github.com/epicchainlabs/epicchain-s3-gw)**: This role manages the S3 Gateway, which integrates EpicChain with Amazon S3-compatible storage services. It handles the configuration and connection to S3 storage, facilitating data storage and retrieval.

## Resources

For more information and detailed configuration settings for each role, please refer to the following documentation:

- **IR Role**: [Detailed Configuration](docs/ir.md)
- **Storage Role**: [Detailed Configuration](docs/storage.md)
- **S3 Gateway Role**: [Detailed Configuration](docs/s3_gw.md)
- **REST Gateway Role**: [Detailed Configuration](docs/rest_gw.md)

Additionally, you can view a real-world usage example in the [ansible-epicchain-template](https://github.com/epicchainlabs/ansible-epicchain-template), which demonstrates how to use these roles in practice.

## Compatibility

The NSPCC EpicChain Ansible Collection is compatible with the following versions:

| EpicChain Node Version | Collection Version |
|------------------------|--------------------|
| 0.37.0                 | 0.0.1              |

Please ensure that you are using a compatible version of EpicChain Node to avoid any potential issues.

## Migration Instructions

If you are migrating from older roles, you can integrate this collection by adding `nspcc.epicchain` to your `collections` array or by using the `nspcc.epicchain.` prefix when calling roles in your playbooks. This approach helps in maintaining compatibility with existing configurations while leveraging the new features provided by this collection.

## Contribution and Support

We welcome contributions to this project. If you encounter any issues or have suggestions for improvements, please submit an issue or a pull request on our [GitHub repository](https://github.com/epicchainlabs/ansible-epicchain). For support and further inquiries, you can reach out to the NSPCC development team through the contact information provided on our [official site](https://epic-chain.org).

## License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file in the repository.

Thank you for using the NSPCC EpicChain Ansible Collection. We hope it helps simplify your EpicChain deployments and management.