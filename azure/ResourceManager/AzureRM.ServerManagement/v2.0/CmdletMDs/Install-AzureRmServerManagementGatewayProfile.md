---
external help file: Microsoft.Azure.Commands.ServerManagement.dll-Help.xml
online version: .\Reset-AzureRmServerManagementGatewayProfile.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.ServerManagement/v2.0/CmdletMDs/Install-AzureRmServerManagementGatewayProfile.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ResourceManager/AzureRM.ServerManagement/v2.0/CmdletMDs/Install-AzureRmServerManagementGatewayProfile.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: Visual Studio China
keywords: powershell, content
manager: Visual Studio China
---

# Install-AzureRmServerManagementGatewayProfile

## SYNOPSIS
Installs a Server Management Gateway profile.

## SYNTAX

```
Install-AzureRmServerManagementGatewayProfile [[-InputFile] <FileInfo>] [-InformationAction <ActionPreference>]
 [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Install-AzureRmServerManagementGatewayProfile** cmdlet installs an Azure Server Management Gateway profile into the correct location.
The file that this cmdlet installs is named profile.json.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -InputFile
Specifies the name of the local file that contains the gateway profile to install.

The file that this cmdlet installs should have been previously saved with the Save-AzureRmServerManagementGatewayProfile cmdlet.

```yaml
Type: FileInfo
Parameter Sets: (All)
Aliases: 

Required: False
Position: 0
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -InformationAction
@{Text=}```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
@{Text=}```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Reset-AzureRmServerManagementGatewayProfile](.\Reset-AzureRmServerManagementGatewayProfile.md)

[Save-AzureRmServerManagementGatewayProfile](.\Save-AzureRmServerManagementGatewayProfile.md)

