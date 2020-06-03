## Management Groups

The organizing structure for resources in Azure has four levels: **Management groups**, **subscriptions**, **resource groups**, and **resources**. The following image shows the relationship of these levels i.e. the hierarchy of organization for the various objects


![Screenshot of the hierarchy for objects in Azure.](../media/hierarchy.png)

+ **Management groups**: These are containers that help you manage access, policy, and compliance for multiple subscriptions. All subscriptions in a management group automatically inherit the conditions applied to the management group.

    + 10,000 management groups can be supported in a single directory.
    + A management group tree can support up to six levels of depth. 
    + This limit doesn't include the Root level or the subscription level.
    + Each management group and subscription can only support one parent.
    + Each management group can have many children.

+ **Subscriptions**: A subscription groups together user accounts and the resources that have been created by those user accounts. For each subscription, there are limits or quotas on the amount of resources you can create and use. Organizations can use subscriptions to manage costs and the resources that are created by users, teams, or projects.

+ **Resource groups**: A resource group is a logical container into which Azure resources like web apps, databases, and storage accounts are deployed and managed.

+ **Resources**: Resources are instances of services that you create, like virtual machines, storage, or SQL databases.

✔️ Read more about [Management Groups](https://docs.microsoft.com/azure/governance/management-groups/overview?azure-portal=true).