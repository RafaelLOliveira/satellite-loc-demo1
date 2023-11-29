# Terraform Script

Script to create IBM Cloud resources using IBM Cloud Schematics/terraform.

### ARCHITECTURE

The diagram shows the target architecture for this cheat sheet. We will create:

- One virtual private cloud (VPC).
- Three virtual server instances (VSI).
- One security group with a security group access control rule.
- Three subnets.
- Three public gateways.
- One floating IP for each vsi (to access the virtual server instance).
- One Red Hat Open Shift Cluster with one Worker Zone per Zone.
- One Cloud Object Storage.
<img src="https://github.com/RafaelLOliveira/terraform-script/blob/main/figures/architecture.png" width="1000"/>



### TUTORIAL

Step by step on how to use IBM Cloud Schematics

1. Access the IBM CLoud Schematics page on IBM Cloud Portal and create a workspace.
2. Copy and paste the repo URL, then click next.
<img src="https://github.com/RafaelLOliveira/terraform-script/blob/main/figures/creating-workspace.png" width="500"/>
3. Put a workspace name, select a Resource Group and a location. Then, click in blue button "Create".
<img src="https://github.com/RafaelLOliveira/terraform-script/blob/main/figures/creating-workspace-2.png" width="800"/>
4. Edit the variables in the Settings field. You can set the region, the vpc name, the resource group, for example. You must have a SSH key in VPC and an API key. Then, click in "Generate a plan", if succeeded, run the "Apply plan" to provision your infraestructure.
<img src="https://github.com/RafaelLOliveira/terraform-script/blob/main/figures/edit-workspace.png" width="900"/>

