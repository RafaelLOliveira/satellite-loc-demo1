# Terraform Script

Script to create IBM Cloud resources using IBM Cloud Schematics/terraform.

**ARCHITECTURE**

The diagram shows the target architecture for this cheat sheet. We will create:

- One virtual private cloud (VPC).
- Three virtual server instances (VSI).
- One security group with a security group access control rule.
- Three subnets.
- Three public gateways.
- One floating IP for each vsi (to access the virtual server instance).
- One Red Hat Open Shift Cluster with one Worker Zone per Zone.
- One Cloud Object Storage.

![architecture_1](satellite-demo.png)
