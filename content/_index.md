---
title: "Konveyor Documentation"
date: 2022-04-14T14:58:17-06:00
draft: false
---
Konveyor is an open source tool that manages applications or portfolios, and streamlines modernizing them to Kubernetes by assessing, prioritizing, and refactoring them. 

The Konveyor community is being refocused on replatforming to container platforms, refactoring and repurchasing.  Functionality will be focused on Tackle and Move2Kube, which becomes Konveyor-transform.  Crane, Forklift, and Pelorus will be transitioned to better suited projects.

## Why Konveyor?
Sysadmins and Developers are tired of the words “Digital Transformation.” They don’t want to hear about the “five keys to digital transformation” or the “seven must-haves to transform.” They are also tired of every vendor presenting their framework and methodology for digital transformation bundled with a bunch of proprietary tools.

Developers and sysadmins want to learn how to actually transform their applications and infrastructure so they can take advantage of new technologies to deliver new capabilities faster, at greater scale, and with higher quality while reducing technical debt. It is clear that one of the technologies that underpins the future of applications and infrastructure is Kubernetes - an open-source system for automating deployment, scaling, and management of containerized applications.

The Konveyor community exists to accelerate sysadmins and developers' journey to Kubernetes. Konveyor is a community of people passionate about helping others modernize and migrate their applications for Kubernetes by building tools, identifying patterns, and providing advice.

## Konveyor projects
Konveyor currently consists of two tools or projects:

* Tackle
* Move2Kube

Together, these two projects comprise the Konveyor community. Moving forward, it is inevitable that demand for each will align with evolving migration strategies and technology trends. New tools could then hypothetically emerge in the Konveyor community empowering users to further extend these containerized applications to edge computing environments, perhaps relying on AI/ML and event-driven architectures. That being said, it is widely expected that there will be ebb and flow with existing project usage, as well as the introduction of entirely new projects altogether.

### Tackle
Tackle provides a series of interrelated tools that allows users to assess, analyze, and ultimately move their applications onto a Kubernetes orchestrated platform. Often considered the most challenging application modernization strategy, adapting applications to a containerized runtime, also offers the largest potential long term impact. This strategy involves making changes to the application and development to take advantage of cloud native capabilities. The tool helps assess the depth of the changes ranging from minimal fixes to adapt the application to containers to a full rewrite of the application in more modern container-friendly runtimes.The Tackle project provides tools that inventory an application environment and identify which workloads are most suitable for refactoring into containers. A common application inventory can also be generated which is then made available as a basis for code execution. The team that is catalyzing this project has experience in these areas from working on tools such as Pathfinder and Windup and will be bringing these experiences to their work on the Tackle project.

The downstream version of Tackle, Migration Toolkit for Applications (MTA), is an assembly of tools that support large-scale Java application modernization and migration projects across a broad range of transformations and use cases. MTA accelerates application code analysis, supports effort estimation, accelerates code migration, and helps users move applications to a variety of platforms including OpenShift.

### Move2Kube

Move2Kube is a project that allows customers to replatform their applications to Kubernetes orchestrated platforms. Replatforming, or “lift, tinker, and shift”, involves changing an underlying technology used by an application while minimizing the need for code change. One area where replatforming is taking place is in the consolidation of container orchestration platforms to Kubernetes. Due to this consolidation, the Move2Kube project was started to focus on accelerating the process of replatform to Kubernetes from platforms such as Swarm and Cloud Foundry. The project translates existing artifacts to Kubernetes artifacts to speed up the process of being able to run applications on Kubernetes.

#### Existing projects
* Ko
* Tackle Hub
* Driver for the user experience and main data store for application profiles and integration point for addons.
* Windup
* Static code analysis
* Tackle Container Advisor
* NLP to determine suitable container image
* Tackle Configuration Discovery
* Transform config files for target runtime
* Tackle Data Intensive Validity Advisor
* Analyze data layer to understand dependencies

[Source](https://github.com/konveyor/konveyor.github.io/blob/main/content/_index.md)
