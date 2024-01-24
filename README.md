**One Identity open source projects are supported through [One Identity GitHub issues](https://github.com/OneIdentity/IdentityManager.Dockerfiles/issues) and the [One Identity Community](https://www.oneidentity.com/community/). This includes all scripts, plugins, SDKs, modules, code snippets or other solutions. For assistance with any One Identity GitHub project, please raise a new Issue on the [One Identity GitHub project](https://github.com/OneIdentity/IdentityManager.Dockerfiles/issues) page. You may also visit the [One Identity Community](https://www.oneidentity.com/community/) to ask questions.  Requests for assistance made through official One Identity Support will be referred back to GitHub and the One Identity Community forums where those requests can benefit all users.**
# IdentityManager.CIEMForAzure

The One Identity Cloud Infrastructure and Entitlement Management solution accelerator, enables you to synchronize the following Azure objects from an Azure Tenant to One Identity Manager
- Management Groups
- Subscriptions
- Resource Groups
- Resources
- Resource Types
- Locations
- Roles
- Role Assignments

Once the objects have been synchronized in to One Identity Manager, you would be able to view the Azure Object role assignments made for the Azure AD user / Azure Service Principal / Azure AD Group.

The One Identity Manager SCIM connector is used to access the Azure objects. The SCIM connector should be installed on a synchronization server to synchronize the Azure objects. The SCIM connector connects to Starling Azure Infrastructure connector and retrieves the Azure objects. The Starling Azure Infrastructure connector uses the Azure Resource Management, Azure Management Groups and Azure Authorization REST API services to retrieve the needed Azure objects

Please follow the instructions of "readme.docx" for using this solution accelerator.

Also, learn more about [CIEM](https://www.oneidentity.com/learn/what-is-ciem.aspx) and [SCIM](https://www.oneidentity.com/what-is-scim/) on our Learning Hub.
