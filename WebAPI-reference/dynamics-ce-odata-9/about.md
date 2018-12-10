---
title: "Dynamics 365 Customer Engagement Web API Reference| MicrosoftDocs"
ms.date: 10/31/2018
ms.service: "powerapps"
ms.topic: "reference"
ms.assetid: 70cdf999-585a-4bc1-a34d-5ee75295295e
author: "kumarvivek"
ms.author: "kvivek"
ms.reviewer: "kvivek"
---
# Web API Reference 
This section contains reference documentation of the types, functions, and actions that constitute the Web API for Common Data Service (CDS) for Apps and Dynamics 365 Customer Engagement. More information:

- [Use the Common Data Service for Apps Web API](/powerapps/developer/common-data-service/webapi/overview)

- [Use the Microsoft Dynamics 365 Customer Engagement Web API](/dynamics365/customer-engagement/developer/use-microsoft-dynamics-365-web-api) 

## In This Section  
 <xref:Microsoft.Dynamics.CRM.EntityTypeIndex>

 An `EntityType` represents an entity type in the OData v4 entity model.  
  
 <xref:Microsoft.Dynamics.CRM.ActionIndex>

 Actions represent operations that may have observable side effects, such as creating or updating records. An action may require parameters and may return a value. Actions may be bound to entity types.  
  
 <xref:Microsoft.Dynamics.CRM.FunctionIndex> 

 A function is an operation that doesn’t have observable side effects. Functions typically retrieve data. They may have parameters and they may return values. Functions may be bound to entity types.  
  
 <xref:Microsoft.Dynamics.CRM.QueryFunctionIndex>

 Query functions are functions that can be used as a filter criteria in a query. They accept parameters and return a Boolean value.  
  
 <xref:Microsoft.Dynamics.CRM.ComplexTypeIndex>

 A `ComplexType` represents structured data that doesn't have a key. Complex types are frequently returned as a response from using an action or function or passed as a parameter to a function..  
  
 <xref:Microsoft.Dynamics.CRM.EnumTypeIndex>

 An `EnumType` represents an enumeration type in an OData v4 entity model.  
  
 <xref:Microsoft.Dynamics.CRM.MetadataEntityTypeIndex>

 Metadata EntityTypes represent the types used in the Dynamics 365 customer engagement metadata model. For information about using these entity types, see [Use the Web API with Dynamics 365 metadata](/dynamics365/customer-engagement/developer/webapi/use-web-api-metadata).  

 <xref:Microsoft.Dynamics.CRM.SolutionIndex>

 Solutions include components that are available in the Web API. Solutions can include custom entities, attributes, entity relationships, and custom actions which change the 
objects available to use in the Web API.   
  
## Reference  
 [OData - the best way to REST](http://www.odata.org/)<br />
 [OData Version 4.0 Part 1: Protocol](http://docs.oasis-open.org/odata/odata/v4.0/os/part1-protocol/odata-v4.0-os-part1-protocol.html)<br />
 [OData Version 4.0 Part 2: URL Conventions](http://docs.oasis-open.org/odata/odata/v4.0/os/part2-url-conventions/odata-v4.0-os-part2-url-conventions.html)<br />
 [OData Version 4.0 Part 3: Common Schema Definition Language (CSDL)](http://docs.oasis-open.org/odata/odata/v4.0/os/part3-csdl/odata-v4.0-os-part3-csdl.html)  
  
## Related Sections
 [Use the Common Data Service for Apps Web API](/powerapps/developer/common-data-service/webapi/overview)

 [Use the Microsoft Dynamics 365 Customer Engagement Web API](/dynamics365/customer-engagement/developer/use-microsoft-dynamics-365-web-api)
 