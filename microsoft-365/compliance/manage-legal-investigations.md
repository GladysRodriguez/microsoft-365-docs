---
title: "Manage legal investigations in Office 365"
f1.keywords:
- NOCSH
ms.author: markjjo
author: markjjo
manager: laurawi
audience: Admin
ms.topic: conceptual
ms.service: O365-seccomp
localization_priority: Normal
ms.collection: M365-security-compliance
search.appverid: 
- MOE150
- MET150
ms.assetid: 2e5fbe9f-ee4d-4178-8ff8-4356bc1b168e
description: "Use eDiscovery cases in the Security & Compliance Center in Office 365 to manage your organization's legal investigation. If you have an E5 subscription, you can further analyze case data by using the text analytics, machine learning, and predictive coding capabilities of Advanced eDiscovery."
---

# Manage legal investigations in Office 365

Organizations have many reasons to respond to a legal case involving certain executives or other employees in your organization. This might involve quickly finding and retaining for further investigation-specific information in email, documents, instant messaging conversations, and other content locations used by people in their day-to-day work tasks. You can perform these and many other similar activities by using the eDiscovery case tools in the security and compliance center.
  
**Want to know how Microsoft manages its eDiscovery investigations?** Here's a [technical white paper](https://go.microsoft.com/fwlink/?linkid=852161) you can download that explains how we use the same Office 365 search and investigation tools to manage our internal eDiscovery workflow.
   
## Manage legal investigations with eDiscovery cases

eDiscovery cases let you control who can create, access, and manage eDiscovery cases in your organization. Use cases to add members and control what types of actions they can perform, place a hold on content locations relevant to a legal case, and use the Content Search tool to search the locations on hold for content that might be responsive to your case. Then you can also export and download those results for further investigation by external reviewers.
  
- [Manage your eDiscovery workflow](ediscovery-cases.md) by creating and using eDiscovery cases for every legal investigation your organization has to undertake 
    
- [Assign eDiscovery permissions](assign-ediscovery-permissions.md) to control who can create and manage eDiscovery cases in your organization 
    
- [Set up compliance boundaries](tagging-and-assessment-in-advanced-ediscovery.md) to control the user content locations that eDiscovery managers can search 
    
- [Search for content](search-for-content.md) in your organization 
    
### Use scripts for advanced scenarios

Like the previous section that listed scripts for content search scenarios, we've also created some Security & Compliance Center PowerShell scripts to help you manage eDiscovery cases.
  
- [Create a eDiscovery hold report](create-a-report-on-holds-in-ediscovery-cases.md) that contains information about all holds associated with eDiscovery cases in your organization 
    
- [Add mailboxes and OneDrive locations](use-a-script-to-add-users-to-a-hold-in-ediscovery.md) for a list of users to an eDiscovery hold 
  
## Manage legal investigations with the Advanced eDiscovery solution in Microsoft 365

The Advanced eDiscovery solution in Microsoft 365 builds on the existing eDiscovery and analytics capabilities in Office 365. This new solution, called *Advanced eDiscovery*, provides an end-to-end workflow to preserve, collect, review, analyze, and export content that's responsive to your organization's internal and external investigations. It also lets legal teams manage the entire legal hold notification workflow to communicate with custodians involved in a case.

Advanced eDiscovery requires an E5 subscription for your Office 365 or Microsoft 365 organization. Alternatively, users with an E3 license require the Advanced Compliance add-on subscription so you can manage them as custodians in an Advanced eDiscovery case.

Here's a quick overview of the built-in workflow in Advanced eDiscovery. For more information, see [Overview of the Advanced eDiscovery solution in Microsoft 365](overview-ediscovery-20.md).

- [Create a case](create-new-ediscovery-case.md) to get started

- [Manage custodians](managing-custodians.md) by adding them to a case and placing a legal hold on content in their mailbox, OneDrive account, and Microsoft Teams they're members of

- [Manage communications](managing-custodian-communications.md) with custodians by automating the legal hold notification process

- [Index custodian data](processing-data-for-case.md) and fix indexing errors so you can effectively collect data for your investigations

- [Collect data](collecting-data-for-ediscovery.md) for a case and add [add it to a review set](collecting-data-for-ediscovery.md#adding-search-results-to-a-review-set) for further investigation

- [View ](view-documents-in-review-set.md) documents, [query](review-set-search.md) data, and [tag](tagging-documents.md) items in a review set

- [Analyze case data](analyzing-data-in-review-set.md) with advanced analytics tools

- [Export case data](exporting-data-ediscover20.md) for review by outside counsel

- [Manage long-running jobs](managing-jobs-ediscovery20.md) in Advanced eDiscovery
