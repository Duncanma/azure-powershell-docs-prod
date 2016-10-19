---
external help file: Microsoft.Azure.Commands.Profile.dll-Help.xml
online version: .\Set-AzureRmContext.md
schema: 2.0.0
ms.assetid: 849CFEF4-7BA5-4766-BB53-B93DFA9BC021
updated_at: 10/18/2016 9:38 PM
ms.date: 10/18/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Profile/v2.1.0/Get-AzureRmContext.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/23cdb8705d4ab9807c0e21b238f3b134a7d49c7d/azureps-cmdlets-docs/ResourceManager/AzureRM.Profile/v2.1.0/Get-AzureRmContext.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmContext

## SYNOPSIS
Gets the metadata used to authenticate Resource Manager requests.

## SYNTAX

```
Get-AzureRmContext [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmContext** cmdlet gets the current metadata used to authenticate Azure Resource Manager requests.

This cmdlet gets the Active Directory account, Active Directory tenant, Azure subscription, and the targeted Azure environment.
By default, Resource Manager cmdlets use these settings when it makes Resource Manager requests.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

###  
This cmdlet returns the account, tenant, and subscription used by Resource Manager cmdlets.

## NOTES

## RELATED LINKS

[Set-AzureRmContext](.\Set-AzureRmContext.md)


