# Vetdata Template - Azure Policy to deploy Azure Lighthouse at Management Group-level

This is specific to Vetdata!

This policy provides access to Vetdata specific groups and it grants the required access to the Global CTG team, the Global CyberSec team, and the Lighthouse Automation Account.

Pre-requisite: Register subscriptions for the RP ManagedServices. Otherwise, the policy will not run.

Deploy this Policy at the management group level to delegate subscriptions within the management group to a managing tenant via Azure Lighthouse. 

This Policy has a DeployIfNotExists effect, evaluating subscriptions within a management group to determine if there are Lighthouse delegations. If not, then a deployment to the specified managing tenant is executed. 