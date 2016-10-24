---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: 979956b7-aa12-432c-b52a-442a9665a57d
schema: 2.0.0
ms.assetid: 03A846AD-4D9B-4612-85F0-ACE35683DFF8
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/New-AzureAclConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/New-AzureAclConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureAclConfig

## SYNOPSIS
Creates an empty ACL configuration object.

## SYNTAX

```
New-AzureAclConfig [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureAclConfig** cmdlet creates an empty access control list (ACL) configuration object.

## EXAMPLES

### Example 1: Create an ACL configuration object
```
PS C:\>$Acl = New-AzureAclConfig
```

This command creates an empty ACL configuration object, and then stores it in the $Acl variable.

## PARAMETERS

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureAclConfig](.\Get-AzureAclConfig.md)

[Remove-AzureAclConfig](.\Remove-AzureAclConfig.md)

[Set-AzureAclConfig](.\Set-AzureAclConfig.md)


