---
page_type: sample
languages:
- yaml
- python
- shell
- C++
products:
- azure-confidential-computing
- azure-kubernetes-service
- azure attestation-service
description: "Confidential containers on AKS samples"
urlFragment: confidential-containers-samples
---

# Confidential container samples

![Flask sample MIT license badge](https://img.shields.io/badge/license-MIT-green.svg)

Confidential containers are a set of capabilities that allow standard containers (Linux or Windows) to run in a hardware root of trusted established enviornment. Confidential containers refer to a set of capabilities that achieves the principles of confidential computing.

The term “confidential containers” refers to docker application (new or existing) containers packaged with additional components if necessary to run on the hardware that provides strong protections of Confidential Computing to improve the overall security posture of the container application and the data-in-use.

Confidential containers run in a hardware based Trusted Execution Environment often referred as an enclave. Containers running in an enclave allows establishing trust to an execution environment to perform any sensitive data processing. Confidential containers is the fastest path to achieve container confidentiality including code integrity, data confidentiality from cloud operator and data integrity. Confidential containers enable taking an existing unmodified docker containers and run in an enclave security.

[Read more here](http://aka.ms/confidentialcontainers)

Use this repository to develop a LUIS application while following DevOps engineering practices that adhere to software engineering fundamentals around source control, testing, CI/CD and release management. This template repository provides a working project structure and GitHub Actions pipelines that you can customize for use with your own project.

For container samples that are programmed to run in the enclaves (enclave aware containers) please visit [this](https://github.com/azure-samples/confidential-computing) samples repo.

**Important:** This repo is aggregated samples based on real world customer scenarios based and may involve Azure Partner Solution or an Open Source Project for its implementation. All implementations in this repo will host Azure Kubernetes Service (AKS) based deployments. Please review the sample repo for pre-requisites to deploy and run this application.

## Prerequisites

- [GitHub account](https://github.com/join)
- [Azure subscription](https://azure.microsoft.com/free/)

## How to use this template repository

This repo is organized by folders that states the sample name followed by the enablers of confidential containers. A typical folder name follows this standard < samplename >-< enabername > :

### Confidential Healthcare Application on Intel SGX based confidential containers

[Confidential HealthCare Implementation with Scone, Confidential Inferencing & Azure Attestation](confidential-healthcare-scone-confinf-onnx/README.md) 

### Confidential Big Data Analytics with Apache Spark and Azure SQL Always Encrypted secured enclaves on Intel SGX based confidential containers

[Confidential Big Data Analytics with Apache Spark on SGX-enabled Containers using Scone](confidential-big-data-spark/README.md)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit <https://cla.opensource.microsoft.com.>

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
