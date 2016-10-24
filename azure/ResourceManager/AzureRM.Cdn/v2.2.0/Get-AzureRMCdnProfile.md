---
external help file: Microsoft.Azure.Commands.Cdn.dll-Help.xml
online version: 64b16ef7-7572-4d48-a290-074b6ea330aa
schema: 2.0.0
ms.assetid: 998C068D-4164-46D1-AF3F-B4E66C38ACF4
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Cdn/v2.2.0/Get-AzureRMCdnProfile.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Cdn/v2.2.0/Get-AzureRMCdnProfile.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmCdnProfile

## SYNOPSIS
Gets a CDN profile.

## SYNTAX

```
Get-AzureRmCdnProfile [-ProfileName <String>] [-ResourceGroupName <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRMCdnProfile** cmdlet gets an Azure Content Delivery Network (CDN) profile and its related information.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ProfileName
Specifies the name of the profile.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group to which the profile belongs.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

###  
This cmdlet returns a profile object.

## NOTES

## RELATED LINKS

[New-AzureRmCdnProfile](.\New-AzureRmCdnProfile.md)

[Remove-AzureRmCdnProfile](.\Remove-AzureRmCdnProfile.md)

[Set-AzureRmCdnProfile](.\Set-AzureRmCdnProfile.md)


