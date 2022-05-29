-   2 minutes

There are several ways you can use Ansible in Azure.

## Azure Marketplace

You can use one of the following images available as part of the Azure Marketplace:

-   Red Hat Ansible on Azure is available as an image on Azure Marketplace, and it provides a fully configured version. It enables easier adoption for those looking to use Ansible as their provisioning and configuration management tool. This solution template will install Ansible on a Linux VM along with tools configured to work with Azure. Including:
    
    -   Ansible (the latest version by default. You can also specify a version number.)
    -   Azure CLI 2.0
    -   MSI VM extension
    -   apt-transport-https
-   Ansible Tower (by Red Hat). Ansible Tower by Red Hat helps organizations scale IT automation and manage complex deployments across physical, virtual, and cloud infrastructures. Built on the proven open-source Ansible automation engine, Ansible Tower includes capabilities that provide extra levels of visibility, control, security, and efficiency necessary for today's enterprises. With Ansible Tower, you can:
    
    -   Provision Azure environments with ease using pre-built Ansible playbooks.
    -   Use role-based access control (RBAC) for secure, efficient management.
    -   Maintain centralized logging for complete auditability and compliance.
    -   Use the large community of content available on Ansible Galaxy.

This offering requires the use of an available Ansible Tower subscription eligible for use in Azure. If you don't currently have a subscription, you can obtain one directly from Red Hat.

## Azure VMs

Another option for running Ansible on Azure is to deploy a Linux VM on Azure virtual machines, which is infrastructure as a service (IaaS).

You can then install Ansible and the relevant components and use that as the control machine.

Note

The Windows operating system isn't supported as a control machine. However, you can run Ansible from a Windows machine by using other services and products like Windows Subsystem for Linux, Azure Cloud Shell, and Visual Studio Code.

For more details about running Ansible in Azure, visit:

-   [Ansible on Azure documentation](https://docs.microsoft.com/en-us/azure/ansible) website
-   [Microsoft Azure Guide](https://docs.ansible.com/ansible/latest/scenario_guides/guide_azure.html)

___

## Next unit: Examine playbook structure

[Continue](https://docs.microsoft.com/en-us/learn/modules/implement-ansible/7-examine-playbook-structure/)

Need help? See our [troubleshooting guide](https://docs.microsoft.com/en-us/learn/support/troubleshooting?uid=learn.wwl.implement-ansible.explore-ansible-azure&documentId=8d064b5c-66ef-f3a5-dcaf-76f83574d6a1&versionIndependentDocumentId=a2f90c57-c938-8a8f-5ca6-5f62f58fbaf9&contentPath=%2FMicrosoftDocs%2Flearn-pr%2Fblob%2Flive%2Flearn-pr%2Fwwl-azure%2Fimplement-ansible%2F6-explore-ansible-azure.yml&url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Flearn%2Fmodules%2Fimplement-ansible%2F6-explore-ansible-azure&author=lumac) or provide specific feedback by [reporting an issue](https://docs.microsoft.com/en-us/learn/support/troubleshooting?uid=learn.wwl.implement-ansible.explore-ansible-azure&documentId=8d064b5c-66ef-f3a5-dcaf-76f83574d6a1&versionIndependentDocumentId=a2f90c57-c938-8a8f-5ca6-5f62f58fbaf9&contentPath=%2FMicrosoftDocs%2Flearn-pr%2Fblob%2Flive%2Flearn-pr%2Fwwl-azure%2Fimplement-ansible%2F6-explore-ansible-azure.yml&url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Flearn%2Fmodules%2Fimplement-ansible%2F6-explore-ansible-azure&author=lumac#report-feedback).