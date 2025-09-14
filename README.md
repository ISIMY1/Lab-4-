# Resiliency 

## Objective

The goal of this lab is to understand how to design and implement resiliency and disaster recovery strategies in Azure. You will explore the difference between planned and unplanned outages, learn what threats you need to protect against, and practice using Azure’s native resiliency constructs to ensure business continuity.

### Skills Learned

By completing this lab, you will gain the ability to plan for both infrastructure and human-related failures using replication, clustering, and safe deployment practices. You will strengthen your understanding of availability requirements, disaster recovery testing, chaos engineering, and multi-region deployments. Finally, you will develop practical experience with Azure Backup, VM replication, and protecting backups as part of a complete resiliency strategy.

### Tools Used

This lab makes use of Azure Backup, Site Recovery, VM replication, availability sets, availability zones, clustering in Azure IaaS, infrastructure as code for repeatable deployments, replication preferences, and chaos engineering practices.

## Steps

You will begin by examining the difference between planned and unplanned disaster recovery scenarios and identifying what you are protecting against, including infrastructure issues and human error. From there, you will define replication requirements and apply safe deployment practices that minimise risk.

Next, you will explore availability concepts, learning to avoid reliance on individual “pet” servers and instead using resilient constructs such as availability zones, availability sets, and multi-region deployments. You will also practice testing your disaster recovery strategy and experiment with chaos engineering to validate resiliency under failure scenarios.

As you move forward, you will compare synchronous and asynchronous replication, review Azure’s built-in resilience support for services, and configure infrastructure as code for consistent recovery deployments. You will also explore VM replication, clustering options in IaaS, and how to balance replication preferences across workloads.

Finally, you will configure Azure Backup, verify backup protection, and ensure that backup data is secure from tampering or deletion. You will complete the lab by reviewing your entire resiliency plan, confirming that it addresses both technical and organizational requirements for disaster recovery in Azure.
