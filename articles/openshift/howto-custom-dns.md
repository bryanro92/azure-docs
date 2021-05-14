---
title: Configure custom dns resources in an Azure Red Hat OpenShift (ARO) cluster
description: Discover how to add a custom DNS server on all of your nodes in Azure Red Hat OpenShift (ARO).
author: b-rossbryan
ms.author: 
ms.service: azure-redhat-openshift
ms.topic: article
ms.date: 05/14/2021
---
# Configure custom dns for your Azure Red Hat OpenShift (ARO) cluster (draft)

This article provides the necessary details that allow you to configure your Azure Red Hat OpenShift cluster (ARO) to use a custom dns server. It contains the cluster requirements for a basic ARO deployment, and more requirements for optional Red Hat and third-party components. An [example](#private-aro-cluster-setup) will be provided at the end on how to configure these requirements with your custom dns. 

## Before you begin

This article assumes that you're creating a new cluster. If you need a basic ARO cluster, see the [ARO quickstart](./tutorial-create-cluster.md).

