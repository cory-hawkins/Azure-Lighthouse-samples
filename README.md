
# Microsoft Azure Lighthouse

Azure Lighthouse provides capabilities to perform cross-tenant management at scale.  We do this by providing you the ability to view and manage multiple customers from a single context. When you log into Azure, you can see all of your customers who you are managing through Azure Lighthouse. [Learn more](https://azure.com/lighthouse).

This repository contains samples to help you use Azure Resource Manager to configure [Azure delegated resource management](https://docs.microsoft.com/azure/lighthouse/concepts/azure-delegated-resource-management) and to configure monitoring and management of customer environments.

The templates shown below can be used to [onboard a customer to Azure Lighthouse](https://docs.microsoft.com/en-us/azure/lighthouse/how-to/onboard-customer). You can deploy these manually, or use the "Deploy to Azure" buttons to deploy directly in the Azure portal.
# Deploy to Azure buttons

Name | Description   | Auto-deploy   | Manual deploy |
-----| ------------- |--------------- |------- 
| CVET Vetdata Azure Lighthouse - Management Group Policy |onboard a *Tenant* | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcory-hawkins%2FAzure-Lighthouse-samples%2Fmaster%2Fcustom-templates%2FPolicy-Delegate-ManagementGroup-Vetdata%2FdeployLighthouseIfNotExistManagementGroup.json) | [templates](https://github.com/cory-hawkins/Azure-Lighthouse-samples/tree/master/custom-templates/Policy-Delegate-ManagementGroup-Vetdata)
| Test Azure Lighthouse - Resource Group Deployment | onboard a *resource group* | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcory-hawkins%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fpolicy-delegate-management-groups%2FdeployLighthouseIfNotExistManagementGroup.json) | [templates](https://github.com/cory-hawkins/Azure-Lighthouse-samples/tree/master/templates/policy-delegate-management-groups)
| Azure Lighthouse - Multiple Resource Group Deployment | onboard multiple *resource groups* | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Frg-delegated-resource-management%2FmultipleRgDelegatedResourceManagement.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/rg-delegated-resource-management)
| Azure Lighthouse + Azure AD PIM - Subscription Deployment  | onboard a *subscriptions* using **Azure AD PIM** (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management-eligible-authorizations%2FdelegatedResourcemanagement-eligible-authorizations.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management-eligible-authorizations)
| Azure Lighthouse + Azure AD PIM - Resource Group Deployment | onboard a *resource groups using **Azure AD PIM** (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Frg-delegatedResourceManagement-eligible-authorizations%2Frg-delegatedResourcemanagement-eligible-authorizations.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/rg-delegatedResourceManagement-eligible-authorizations)
| Azure Lighthouse + Azure AD PIM - Multiple Resource Group Deployment | onboard multiple *resource groups* using **Azure AD PIM** (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Frg-delegatedResourceManagement-eligible-authorizations%2FmultipleRgDelegatedResourceManagement-eligible-authorizations.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/rg-delegatedResourceManagement-eligible-authorizations)

**Special Instructions (for MSPs):**
To customize, fork this repository, and follow [these](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-azure-button) instructions to update the links to enable your customers to deploy your templates into their Azure environments.

