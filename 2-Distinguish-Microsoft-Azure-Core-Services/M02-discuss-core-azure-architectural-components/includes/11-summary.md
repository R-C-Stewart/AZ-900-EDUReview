## Summary

Microsoft provides more global presence than any other cloud provider with over 54 regions distributed worldwide. This infrastructure gives you the scale needed to bring your applications closer to users around the world. Azure also has dedicated regions to support government use and applications that need to be deployed in China so you can ensure data security and residency and meet compliance and resilience requirements for your customers no matter what type of business requirements you have.

We've taken a look at several features you can use to put organization and control around your Azure resources. 

* We talked about how resource groups worked, and some ways you can use them to organize your resources.

By using these tools throughout your Azure environment, you'll have greater organization across your Azure resources.

## Learn more

Visit the following links to learn more about some of the topics we explored in this module.

- [Azure regions](https://azure.microsoft.com/global-infrastructure/regions/)
- [Azure geographies](https://azure.microsoft.com/global-infrastructure/geographies/)
- [Azure Service Level Agreements](https://azure.microsoft.com/support/legal/sla/summary/)
- [Designing resilient applications for Azure](https://docs.microsoft.com/azure/architecture/resiliency/)
- [Criteria for choosing an Azure compute service](https://docs.microsoft.com/azure/architecture/guide/technology-choices/compute-comparison#availability)

## Clean up

Let's clean up the resources that we created. Since we deployed everything in a single resource group, cleaning up is easy.

1. Go ahead and pull up the [Azure portal](https://portal.azure.com/?azure-portal=true) in a web browser if you haven't already. In the search box in the top navigation bar, search for **msftlearn-core-infrastructure-rg** and click on the resource group.

1. In the **Overview** pane, click **Delete resource group**. Enter the **msftlearn-core-infrastructure-rg** resource group name to confirm, and click **Delete**.