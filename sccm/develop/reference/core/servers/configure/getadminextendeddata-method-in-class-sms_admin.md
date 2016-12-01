---
title: "GetAdminExtendedData Method | Microsoft Docs"
ms.custom: ""
ms.date: "09/20/2016"
ms.prod: "configuration-manager"
ms.reviewer: ""
ms.suite: ""
ms.technology:
  - "configmgr-other"
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to:
  - "System Center Configuration Manager (current branch)"
ms.assetid: 25bb4ce9-df34-436b-a74a-6768963b0bd1
caps.latest.revision: 8
author: "shill-ms"
ms.author: "v-suhill"
manager: "mbaldwin"
---
# GetAdminExtendedData Method in Class SMS_Admin
The `GetAdminExtendedData` Windows Management Instrumentation (WMI) class method, in Configuration Manager, gets the extended data that the current user and its groups have for a given type.  

> [!WARNING]
>  This method is reserved for internal use.  

 The following syntax is simplified from Managed Object Format (MOF) code and defines the method.  

## Syntax  

```  
sint32 GetAdminExtendedData(  
    [in] uint32 Type,   
    [out] string ExtendedData[]);  
};  
```  

#### Parameters  
 `Type`  
 Data type: `UInt32`  

 Qualifiers: [in]  

 The type associated with the user.  

 `ExtendedData`  
 Data type: `String` Array  

 Qualifiers: [out]  

 The extended data that the current user and its groups have for a given type.  

## Return Values  
 An `SInt32` data type that is 0 to indicate success or non-zero to indicate failure.  

## Requirements  

## Runtime Requirements  
 For more information, see [Configuration Manager Server Runtime Requirements](../../../../../develop/core/reqs/server-runtime-requirements.md).  

## Development Requirements  
 For more information, see [Configuration Manager Server Development Requirements](../../../../../develop/core/reqs/server-development-requirements.md).  

## See Also  
 [SMS_Admin Server WMI Class](../../../../../develop/reference/core/servers/configure/sms_admin-server-wmi-class.md)