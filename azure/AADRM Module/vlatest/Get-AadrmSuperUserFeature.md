---
external help file: Microsoft.RightsManagementServices.Online.Admin.PowerShell.dll-Help.xml
online version: http://go.microsoft.com/fwlink/?LinkId=400615
schema: 2.0.0
ms.assetid: 4897E667-E8EE-47A0-9F43-2FA3A76D9D38
updated_at: 10/19/2016 7:10 PM
ms.date: 10/19/2016
content_git_url: https://github.com/Azure/azure-docs-powershell-aip/blob/master/Azure%20Information%20Protection/AADRM%20Module/vlatest/Get-AadrmSuperUserFeature.md
gitcommit: https://github.com/Azure/azure-docs-powershell-aip/blob/c584db022c82c9f9aca042c591590162f9d96d2b/Azure%20Information%20Protection/AADRM%20Module/vlatest/Get-AadrmSuperUserFeature.md
ms.topic: reference
ms.prod: powershell
ms.service: rights-management
ms.technology: Azure Powershell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AadrmSuperUserFeature

## SYNOPSIS
Gets the status of the super user feature for Rights Management.

## SYNTAX

```
Get-AadrmSuperUserFeature [<CommonParameters>]
```

## DESCRIPTION
The **Get-AadrmSuperUserFeature** cmdlet gets the status of the super user feature for Azure Rights Management in your organization.
The feature can be enabled or disabled.
By default, it is disabled.
For more information about super users, see Configuring super users for Azure Rights Management and discovery services or data recoveryhttps://docs.microsoft.com/rights-management/deploy-use/configure-super-users (https://docs.microsoft.com/rights-management/deploy-use/configure-super-users) on the Microsoft documentation site.

## EXAMPLES

### Example 1: Get the status of the super user feature
```
PS C:\>Get-AadrmSuperUserFeature
Enabled
```

This command gets the status (Enabled or Disabled) of the super user feature in your organization.

## PARAMETERS

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Disable-AadrmSuperUserFeature](.\Disable-AadrmSuperUserFeature.md)

[Enable-AadrmSuperUserFeature](.\Enable-AadrmSuperUserFeature.md)


