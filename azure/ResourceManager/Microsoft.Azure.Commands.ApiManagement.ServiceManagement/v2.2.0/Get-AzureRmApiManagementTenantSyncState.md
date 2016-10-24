---
external help file: Microsoft.Azure.Commands.ApiManagement.ServiceManagement.dll-Help.xml
online version: 3b5fc8e3-5a02-4f3b-81f0-51dfe47a201b
schema: 2.0.0
ms.assetid: 288EF15B-FE5C-44AE-ABD5-2B92F408B9EB
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/Microsoft.Azure.Commands.ApiManagement.ServiceManagement/v2.2.0/Get-AzureRmApiManagementTenantSyncState.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/Microsoft.Azure.Commands.ApiManagement.ServiceManagement/v2.2.0/Get-AzureRmApiManagementTenantSyncState.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmApiManagementTenantSyncState

## SYNOPSIS
Gets the status of the most recent synchronization between the configuration database and the Git repository.

## SYNTAX

```
Get-AzureRmApiManagementTenantSyncState -Context <PsApiManagementContext> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmApiManagementTenantSyncState** cmdlet gets the status of the most recent synchronization between the configuration database and the Git repository.

## EXAMPLES

### Example 1: Get the status of the most recent synchronization
```
PS C:\>Get-AzureRmApiManagementTenantSyncState -Context $ApimContext
```

This command gets the status of the most recent synchronization between the configuration database and the Git repository.

## PARAMETERS

### -Context
Specifies a **PsApiManagementContext** object.

```yaml
Type: PsApiManagementContext
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.Commands.ApiManagement.ServiceManagement.Models.PsApiManagementAccessInformation

## NOTES

## RELATED LINKS


