---
description: "Learn more about: ISSOMapping.Create Method"
title: "ISSOMapping.Create Method | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 2f6c9a3a-8571-4373-991f-fabe9c7795d0
caps.latest.revision: 3
author: "christopherhouser"
ms.author: "hisdocs"
manager: "anneta"
---
# ISSOMapping.Create Method
The **Create** method creates the mapping.  
  
## Syntax  
  
```cpp#  
  
HRESULT Create(  
LONG lFlags  
);  
```  
  
```vb  
  
Sub Create(  
lFlags As Long  
)  
```  
  
#### Parameters  
 `lFlags`  
 For the current release, *lFlags* can be set to SSO_FLAG_REFRESH only.  
  
 `lFlags`  
 For the current release, *lFlags* can be set to SSO_FLAG_REFRESH only.  
  
## Return Value  
 This method returns an HRESULT indicating whether it completed successfully. For more details, see the Error Values section.  
  
 Not applicable.  
  
## Error Values  
 This method returns an HRESULT containing one of the values in the following table.  
  
 This method indicates errors by setting the **Number** property of the global **Err** object to one of the values in the following table.  
  
|Value|Description|  
|-----------|-----------------|  
|S_OK|The method succeeded.|  
|E_ACCESSDENIED|Access is denied to the caller.|  
|E_INVALIDARG|An invalid parameter was detected.|  
  
## Requirements  
 **Platforms:**  [!INCLUDE[btsPlatformsComApis](../includes/btsplatformscomapis-md.md)]  
  
## See Also  
 [ISSOMapping Interface (COM)](../esso/issomapping-interface-com.md)   
 [ISSOMapping Members](../esso/issomapping-members.md)   
 [Programming with Enterprise Single Sign-On](../esso/programming-with-enterprise-single-sign-on.md)
