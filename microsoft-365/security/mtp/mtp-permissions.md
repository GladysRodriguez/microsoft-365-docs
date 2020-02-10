---
title: Manage access to Microsoft Threat Protection data in the Microsoft 365 security center
description: Learn how to manage permissions to data in Microsoft Threat Protection 
keywords: access, permissions, MTP, Microsoft Threat Protection, M365, security, MCAS, MDATP, Cloud App Security, Microsoft Defender Advanced Threat Protection, scope, scoping, RBAC
search.product: eADQiWindows 10XVcnh
ms.prod: microsoft-365-enterprise
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
f1.keywords:
- NOCSH
ms.author: lomayor
author: lomayor
ms.localizationpriority: medium
manager: dansimp
audience: ITPro
ms.collection: M365-security-compliance 
ms.topic: conceptual
search.appverid: 
- MOE150
- MET150
---

# Manage access to Microsoft Threat Protection

**Applies to:**
- Microsoft Threat Protection

[!INCLUDE [Prerelease information](../includes/prerelease.md)]

Accounts assigned the following Azure Active Directory (AD) roles can access Microsoft Threat Protection functionality and data:
- Global administrator
- Security administrator
- Security Operator
- Global Reader
- Security Reader

To review accounts with these roles, [view Permissions in the Microsoft 365 security center](https://security.microsoft.com/permissions).

## Access to functionality
Access to specific functionality is determined by your [Azure AD role](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-assign-admin-roles). Contact a global administrator if you need access to specific functionality that requires you or your user group be assigned a new role.

### Approve pending automated tasks
[Automated investigation and remediation](mtp-autoir-actions.md) can take action on emails, forwarding rules, files, persistence mechanisms, and other artifacts found during investigations. To approve or reject pending actions that require explicit approval, you must have certain roles assigned in Microsoft 365. To learn more, see [Action center permissions](mtp-action-center.md#required-permissions-for-action-center-tasks).

## Access to data
Access to Microsoft Threat Protection data can be controlled using the scope assigned to user groups in Microsoft Defender ATP role-based access control (RBAC). If your access has not been scoped to a specific set of devices in the Microsoft Defender ATP, you will have full access to data in Microsoft Threat Protection. However, once your account is scoped, you will only see data about the devices in your scope.

For example, if you belong to only one user group with a Microsoft Defender ATP role and that user group has been given access to sales devices only, you will see only data about sales devices in Microsoft Threat Protection. [Learn more about RBAC settings in Microsoft Defender ATP](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac)

### Microsoft Cloud App Security access controls
During the preview, Microsoft Threat Protection does not enforce access controls based on  Cloud App Security settings. Access to Microsoft Threat Protection data is not affected by these settings.

## Related topics

- [Azure AD roles](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-assign-admin-roles)
- [Microsoft Defender ATP RBAC](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac)
- [Cloud App Security roles](https://docs.microsoft.com/cloud-app-security/manage-admins)