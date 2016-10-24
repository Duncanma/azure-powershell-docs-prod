---
external help file: Microsoft.Azure.Commands.Profile.dll-Help.xml
online version: 849cfef4-7ba5-4766-bb53-b93dfa9bc021
schema: 2.0.0
ms.assetid: F69EA38D-9914-454E-9B45-9262B7413042
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Profile/v2.2.0/Select-AzureRmProfile.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Profile/v2.2.0/Select-AzureRmProfile.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Select-AzureRmProfile

## SYNOPSIS
Loads Azure authentication information from a file.

## SYNTAX

### InMemoryProfile
```
Select-AzureRmProfile [-Profile] <AzureRMProfile> [<CommonParameters>]
```

### ProfileFromDisk
```
Select-AzureRmProfile [-Path] <String> [<CommonParameters>]
```

## DESCRIPTION
The **Select-AzureRmProfile** cmdlet loads authentication information from a file to set the Azure environment and context.
Cmdlets that you run in the current session use this information to authenticate requests to Azure Resource Manager.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Path
Specifies the path of profile information saved by using the Save-AzureRmProfile cmdlet.

```yaml
Type: String
Parameter Sets: ProfileFromDisk
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureRMProfile
Parameter Sets: InMemoryProfile
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureRmContext](.\Get-AzureRmContext.md)

[Save-AzureRmProfile](.\Save-AzureRmProfile.md)


