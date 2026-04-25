# iac-infra-for-demo

Terraform infrastructure for demo Azure environments. The repository contains reusable modules and stack definitions for resource groups, AKS, and storage.

## Layout

- `modules/` contains reusable Terraform modules.
- `stacks/` contains deployable stack entry points.
- `azure-pipelines.yml` defines the Azure DevOps pipeline used to deploy a selected stack.

## Notes

- Replace the placeholder pipeline defaults before running deployments in a shared environment.
- Store Azure credentials and service connection details in Azure DevOps, not in the repository.
