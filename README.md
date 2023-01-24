# Azure Lighthouse Managed Offer - Discovery and Assessment
Stores the Azure Lighthouse Managed Service Offer template that can be used to provide delegation to customer environments from objects within the Softcat Partner account

The following permissions are included in this lighthouse offer.

# Delegated Permissions

| User/Group                                    | Delegated Permission                                 | Access Type | Max Duration | MFA   | Approvers                      |
| --------------------------------------------- | ---------------------------------------------------- | ----------- | ------------ | ---   | ------------------------------ |
| ALH - Managed Azure Customer Reliability Engineers                 | Reader                                               | Permanent   | -            | -     | -                              |
| ALH - Managed Azure Customer Reliability Engineers                 | Managed Services Registration Assignment Delete Role | Permanent   | -            | -     | -                              |
| ALH - Managed Azure Solutions Design                               | Reader                                               | Permanent   | -            | -     | 
# Deploy to Azure 

Use the below button to deploy this Azure Lighthouse offer to a tenant.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSoftcatMS%2Fazure-lighthouse-managedoffer-discovery%2Fmain%2Fproduction-lighthouse-offer-discovery.json)
