# az-clusterfileserver
Powershell Module for configuring guest cluster file server in Azure using Storage Spaces Direct.

Prerequisites:
1.	An Azure subscription, a resource group, a Vnet and a subnet needs to be provisioned already.
2.	Two or more Windows VMs with Windows Server 2019 DC should be deployed.
3.	An Azure basic or standard internal load balancer needs to be deployed in the subnet where the VMs are deployed.
4.	A DC needs to be deployed in azure VNet or if its on-premises, there should be a connection between Azure Vnet and on-prem DC.
5.	Command Update-FileServerRoleIP from the module needs to be run after the load balancing rule is configured for the file server role IP address.
