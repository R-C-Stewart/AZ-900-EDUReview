Choose the best response for each of the questions below. Then select “Check your answers.”

## quiz title: Check your knowledge

## Multiple Choice

Which Azure compute resource can you use to deploy to manage a set of identical virtual machines?

() Virtual machine availability sets{{That's incorrect.}}
() Virtual machine availability zones{{That's incorrect.}}
(x) Virtual machine scale sets{{That's correct. Virtual machine scale sets let you deploy and manage a set of identical virtual machines.}}

## Multiple Choice

Which of the following should you use when you are concerned only about the code running your service and not the underlying platform or infrastructure?

() Azure App Service{{That's incorrect.}}
() Azure Container Instances{{That's incorrect.}}
(x) Azure Functions{{That's correct. Azure Functions are ideal when you're concerned only about the code running your service and not the underlying platform or infrastructure.}}

## Multiple Choice

Azure Resource Manager templates use which format?

() HTML{{That's incorrect.}}
(x) JSON{{That's correct. Resource Manager templates are JSON files that define the resources you need to deploy for your solution. You can use template to easily re-create multiple versions of your infrastructure, such as staging and production.}}
() XML{{That's incorrect.}}

## Multiple Choice

Which of the following services is a distributed network of servers that can efficiently deliver web content to users?

() Azure App Services{{That's incorrect.}}
(x) Azure Content Delivery Network{{That's correct. A Content Delivery Network is a distributed network of servers that can efficiently deliver web content to users.}}
() Azure Cosmos DB{{That's incorrect.}}

## Multiple Choice

Which of the following is optimized for storing massive amounts of unstructured data, such as videos and images?

(x) Blobs{{That's correct. Azure Blob storage is Microsoft's object storage solution for the cloud. Blob storage is optimized for storing massive amounts of unstructured data, such as text or binary data.}}
() Files{{That's incorrect.}}
() Queues{{That's incorrect.}}

## Multiple Choice

Which is true about Azure Load Balancer?

(x) Azure Load Balancer distributes traffic among similar systems, making your services more highly available.{{That's correct. If one system is unavailable, Azure Load Balancer stops sending traffic to it. It then directs traffic to one of the responsive servers.}}
() Azure Load Balancer works with internet-facing traffic only.{{That's incorrect.}}
() You must use Azure Load Balancer if you want to distribute traffic among your virtual machines running in Azure.{{That's incorrect.}}

## Multiple Choice

Which of the following is true about virtual networks?

() A virtual network accepts network traffic on all ports. You configure the firewall through virtual machines.{{That's incorrect.}}
() Virtual networks are always reachable from the internet.{{That's incorrect.}}
(x) You configure virtual networks through software.{{That's correct. Software enables you to treat a virtual network just like your own network. Azure maintains the physical hardware for you.}}

## Multiple Choice

You are creating a Windows virtual machine in the Azure portal. Which options from the components below is a required element?

(x)Resource Group {{That's correct. Virtual Machines must reside in a resource group.}}
()Availability Options {{That's incorrect. Virtual Machines do not necessarily require a public IP address, availability options, nor additional data disks; these are optional components.}}
()Public IP Address {{That's incorrect. Virtual Machines do not necessarily require a public IP address, availability options, nor additional data disks; these are optional components. }}

## Multiple Choice

You are creating an Azure Container Instance (ACI) in the Azure portal.

(x)Image Source {{That's correct. You can choose between three networking options for your container instance – Public, Private, or None. None will not create either a public IP or virtual network. You will still be able to access your container logs using the command line. Because you can designate “None”, you are not required to have ports nor ports protocols designated.}}
()DNS Name Label {{That's incorrect. Only a Resource Group (and an Image Source) are required.}}
()Ports / Ports Protocol {{That's incorrect. Only a Resource Group (and an Image Source) are required.}}

## Multiple Choice

Which is a fully-managed MySQL database service for app developers?

(x)Azure Database for MySQL {{That's correct. EAzure Database for MySQL is a fully-managed MySQL database service for app developers.}}
()Azure Cosmos DB {{That's incorrect. Azure Cosmos DB is a globally-distributed database service that enables you to elastically and independently scale throughput and storage.}}
()Azure SQL Database {{That's incorrect. Azure SQL Database is a relational database as a service (DaaS) based on the latest stable version of the Microsoft SQL Server database engine.}}

## Multiple Choice

Azure virtual machines you create for Windows Virtual Desktop must be: (choose the best answer)

(x)Standard domain-joined {{That's correct. Standard domain-joined (or can also be Hybrid AD-joined). Virtual machines can't be Azure AD-joined.}}
()Azure AD-joined {{That's incorrect.}}
()Stand alone (workgroup) {{That's incorrect.}}

## Multiple Choice

You want to "lift and shift" an application to the cloud which already uses the native file system APIs to share data between it and other applications running in Azure.
Which storage solution should you use?

(x)Azure Files {{That's correct. Azure Files provides an SMB interface, client libraries, and a REST interface that allows access from anywhere to stored files. When you need to "lift and shift" an application to the cloud which already uses the native file system APIs to share data between it and other applications running in Azure, Azure Files is the best choice.}}
()Azure Blobs {{That's incorrect.}}
()Azure Disks {{That's incorrect.}}