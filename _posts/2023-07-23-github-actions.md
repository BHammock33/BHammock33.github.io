---
layout: post
title: CI/CD pipline with Github Actions
subtitle: Working with Github actions on Azure
---

I am working through microsofts Create Cloud Native apps learning path right now. Today's lesson was all about using github actions to enforce the CI/CD pipeline often looked for in Cloud Native app devOps. With GitHub actions I was able to create a template for an Azure Kubernetes Service and use the GitHub actions functionality to create a new AKS and deploy it into my resource group. By using these actions we can automate deployment of Artifacts and ensure constant uptime. It also allows for the embedding of Secrets in the actions so sensitive info can be securely stored and then saved for repreated use (My Azure subscription credentials and ID in this instance). [Check out the repo here](https://github.com/BHammock33/cna-devops-03/tree/main) which just contains the README as I deleted the resource group to avoid unecessary costs while learning. 