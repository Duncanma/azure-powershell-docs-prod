---
external help file: Microsoft.Azure.Commands.ApiManagement.ServiceManagement.dll-Help.xml
online version: 3b5fc8e3-5a02-4f3b-81f0-51dfe47a201b
schema: 2.0.0
ms.assetid: 236B4436-E8AD-42B4-922C-E2E1406CAFC2
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/Microsoft.Azure.Commands.ApiManagement.ServiceManagement/v2.2.0/Get-AzureRmApiManagementTenantAccess.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/Microsoft.Azure.Commands.ApiManagement.ServiceManagement/v2.2.0/Get-AzureRmApiManagementTenantAccess.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmApiManagementTenantAccess

## SYNOPSIS
Gets the access configuration for a tenant.

## SYNTAX

```
Get-AzureRmApiManagementTenantAccess -Context <PsApiManagementContext> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmApiManagementTenantAccess** cmdlet gets the tenant access configuration for a tenant.

## EXAMPLES

### Example 1: Get tenant access configuration
```
PS C:\>Get-AzureRmApiManagementTenantAccess -Context $ApimContext
```

This command gets the tenant access configuration for the specified context.

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

[Set-AzureRmApiManagementTenantAccess](.\Set-AzureRmApiManagementTenantAccess.md)


