---
description: "Learn more about: Enterprise Single Sign-On Flags"
title: "Enterprise Single Sign-On Flags | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: cece2636-d234-439d-8422-0ba7299acdac
caps.latest.revision: 4
author: "christopherhouser"
ms.author: "hisdocs"
manager: "anneta"
---
# Enterprise Single Sign-On Flags
The following flags are used with the Microsoft® Host Integration Server Enterprise Single Sign-On (SSO) methods.  
  
## Common flags  
  
|Member name|Value|  
|-----------------|-----------|  
|SSO_FLAG_NONE|0x00000000|  
|SSO_FLAG_REFRESH|0x00000001|  
|SSO_FLAG_ENABLED|0x00000002|  
|SSO_FLAG_RUNTIME|0x00000004|  
|SSO_FLAG_SSO_EXTERNAL_TO_WINDOWS|0x00000008|  
|SSO_FLAG_SSO_VERIFY_EXTERNAL_CREDS|0x00000010|  
|SSO_FLAG_ALLOW_TICKETS|0x00000020|  
|SSO_FLAG_VALIDATE_TICKETS|0x00000040|  
|SSO_FLAG_ADMIN_ENABLED|0x80|  
|SSO_FLAG_READ_MODIFY_WRITE|0x100|  
|SSO_FLAG_REPLAY|0x100|  
  
## Password synchronization flags  
  
|Member name|Value|  
|-----------------|-----------|  
|SSO_FLAG_PARTIAL_SYNC_FROM_WINDOWS_TO_DB|0x00000100|  
|SSO_FLAG_PARTIAL_SYNC_FROM_EXTERNAL_TO_DB|0x00000200|  
|SSO_FLAG_FULL_SYNC_FROM_WINDOWS_TO_EXTERNAL|0x00000400|  
|SSO_FLAG_FULL_SYNC_FROM_EXTERNAL_TO_WINDOWS|0x00000800|  
|SSO_FLAG_SYNC_VERIFY_EXTERNAL_CREDS|0x00001000|  
|SSO_FLAG_SYNC_PROVIDE_OLD_EXTERNAL_CREDS|0x00002000|  
|SSO_FLAG_SYNC_ALLOW_MAPPING_CONFLICTS|0x00004000|  
  
## Application flags  
  
|Member name|Value|  
|-----------------|-----------|  
|SSO_FLAG_APP_GROUP|0x10000|  
|SSO_FLAG_APP_USES_GROUP_MAPPING|0x00010000|  
|SSO_FLAG_APP_EXTERNAL_NAME_SAME|0x00020000|  
|SSO_FLAG_APP_ALLOW_LOCAL|0x40000|  
|SSO_FLAG_APP_ADMIN_SAME|0x80000|  
|SSO_FLAG_APP_CONFIG_STORE|0x100000|  
|SSO_FLAG_APP_TICKET_TIMEOUT|0x200000|  
|SSO_FLAG_APP_ADAPTER|0x400000|  
|SSO_FLAG_APP_FILTER_BY_TYPE|0x1|  
|SSO_FLAG_APP_SENSITIVE_INFO_REMOVED|0x80000000|  
|SSO_FLAG_APP_DIRECT_PASSWORD_SYNC|0x2000000|  
|SSO_FLAG_APP_WINDOWS_CREDS|0x800000|  
|SSO_FLAG_APP_RESTRICTED_CREDS|0x1000000|  
  
## Application Type flags  
  
|Member name|Value|  
|-----------------|-----------|  
|SSO_APP_TYPE_NONE|0|  
|SSO_APP_TYPE_INDIVIDUAL|0x1|  
|SSO_APP_TYPE_GROUP|0x2|  
|SSO_APP_TYPE_CONFIG_STORE|0x4|  
|SSO_APP_TYPE_HOST_GROUP|0x8|  
|SSO_APP_TYPE_PS_ADAPTER|0x10|  
|SSO_APP_TYPE_PS_GROUP_ADAPTER|0x20|  
  
## Mapping flags  
  
|Member name|Value|  
|-----------------|-----------|  
|SSO_FLAG_MAPPING_REQUIRES_WINDOWS_PASSWORD|0x01000000|  
|SSO_FLAG_MAPPING_REQUIRES_EXTERNAL_CREDS|0x02000000|  
|SSO_FLAG_MAPPING_ENABLE_AUDIT|0x04000000|  
|SSO_FLAG_MAPPING_CONFIG_STORE|0x8000000|  
|SSO_FLAG_MAPPING_ADMIN|0x10000000|  
|SSO_FLAG_MAPPING_HOSTGROUP|0x20000000|  
|SSO_FLAG_MAPPING_GROUP|0x40000000|  
|SSO_FLAG_MAPPING_HIDE|0x80000000|  
|SSO_FLAG_MAPPING_CHECK|0x100000|  
  
## Field information flags  
  
|Member name|Value|  
|-----------------|-----------|  
|SSO_FLAG_FIELD_INFO_MASK|0x10000000|  
|SSO_FLAG_FIELD_INFO_SYNC|0x20000000|  
  
## Requirements  
 **Platforms:** Windows Server 2003 R2 SP2, Windows Vista SP2, Windows 7, Windows Server 2008 SP2, Windows Server 2008 R2
