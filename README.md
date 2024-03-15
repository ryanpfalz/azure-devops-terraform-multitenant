# azure-devops-terraform-multitenant

---

| Page Type | Languages     | Key Services             | Tools     |
| --------- | ------------- | ------------------------ | --------- |
| Sample    | HCL <br> YAML | Azure DevOps (Pipelines) | Terraform |

---

# Deploying infrastructure across multiple Azure tenants and subscriptions with Azure DevOps and Terraform

Deploying infrastructure as code via Azure Pipelines is a common use case, especially to a single Azure tenant/subscription. However, there are scenarios where you may need to dynamically deploy infrastructure across multiple tenants and subscriptions. There are several limitations that one might experience when trying to configure and execute this scenario; this codebase demonstrates how to circumvent these limitations and dynamically deploy infrastructure to multiple Azure tenants and subscriptions using repeatable workflows.

This codebase provides a simple use case and starting point that should be modified and expanded into more complex scenarios.

## Prerequisites

- [An Azure Subscription](https://azure.microsoft.com/en-us/free/) - for hosting cloud infrastructure
- [Azure DevOps](https://azure.microsoft.com/en-us/products/devops/) - for running pipelines
- [Terraform (optional on local machine)](https://www.terraform.io/downloads.html) - for infrastructure as code

## Running this sample

### Configuring target tenants and subscriptions

#### Setting up service connections

#### Configuration files

### Pipelines

#### Template Pipeline

#### Execution Pipeline

### Additional notes

- Parallelism

## Potential Use Cases

An organization may consider deploying infrastructure across multiple tenants and subscriptions for various reasons, including:

- Multi-tenant solutions
- Enterprise resource segregation
- Regulatory compliance
- Enabling consistent boilerplate deployment stamps across tenants

## Workflow

![Workflow](./docs/images/workflow_diagram.png)

1. TODO
2. TODO
3. TODO
4. TODO
5. TODO

## Additional Resources

- TODO
