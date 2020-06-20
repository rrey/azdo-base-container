# azure-devops-base-container

Base image for Azure Devops container based jobs.

See [Microsoft documentation](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/container-phases?view=azure-devops#non-glibc-based-containers)

# About

Azure Devops has requirements on containers used in a CI pipeline. You can not simply use an image with a tool installed like in Githhub Actions or Gitlab...
The image built from this repository is meant to be used as the base image for your containers in Azure Devops. It contains the requirements described in [Azure doc](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/container-phases?view=azure-devops#non-glibc-based-containers)
