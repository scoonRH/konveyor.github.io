+++
title = "Former Tools"
date = 2022-12-29T14:13:07-07:00
weight = 3
chapter = false
pre = "<b> </b>"
+++

# Former Konveyor Tools

The Konveyor community is being refocused on replatforming to container platforms, refactoring and repurchasing.  Functionality will be focused on Tackle and Move2Kube, which becomes Konveyor-transform.  Crane, Forklift, and Pelorus will be transitioned to better suited projects.

## Crane
Crane is another rehosting tool that meets a different use case. It allows organizations to migrate applications between Kubernetes clusters. There are many times when developers and operations teams want to migrate between older and newer versions of Kubernetes, evacuate a cluster, or migrate to different underlying infrastructure. In an ideal scenario, this would be a redeployment of the application, but in reality we have found that many users need a solution for migrating persistent data and the objects within Kubernetes namespaces continuously.

The downstream version of Crane, Migration Toolkit for Containers (MTC), is available for Red Hat OpenShift customers interested in moving from version 3.x to 4, as well as from different clusters of version 4. It is fully supported and available on OpenShift Operator Hub.

## Forklift
Forklift is focused on migrating virtual machines to Kubernetes and provides the ability to migrate multiple virtual machines to KubeVirt with minimal downtime. It allows organizations to rehost, or “lift and shift'' applications residing on these VMs. While rehosting doesn’t provide the same depth of benefits as replatforming or refactoring, it’s the first step in the right direction. It’s often useful to have all the unmodified development workloads in Kubernetes as a basecamp for further transformations, or in cases where development teams may not have the ability to change or modify code, such as with vendor provided software. Rehosting also helps teams enjoy the benefits of the new platform with less friction in improving process and culture.

The downstream version of this tool, Migration Toolkit for Virtualization (MTV) is available to Red Hat customers interested in moving vSphere virtual machines to OpenShift Virtualization. As of February 2021, it is available as tech preview.

[Source](https://github.com/konveyor/konveyor.github.io/blob/main/content/former/_index.md)