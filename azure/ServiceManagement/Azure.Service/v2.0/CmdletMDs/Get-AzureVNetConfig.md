---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: .\Get-AzureVNetSite.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v2.0/CmdletMDs/Get-AzureVNetConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v2.0/CmdletMDs/Get-AzureVNetConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: Visual Studio China
keywords: powershell, content
manager: Visual Studio China
---

# Get-AzureVNetConfig

## SYNOPSIS
Gets the Azure virtual network configuration from the current subscription.

## SYNTAX

```
Get-AzureVNetConfig [-ExportToFile <String>] [-Profile <AzureSMProfile>]
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureVNetConfig** cmdlet retrieves the virtual network configuration of the current Azure subscription.
If the *ExportToFile* parameter is specified, a network configuration file is created.

## EXAMPLES

### Example 1: Get the virtual network configuration of a current Azure subscription
```
PS C:\>Get-AzureVNetConfig
```

This command gets the virtual network configuration of the current Azure subscription and displays it.

### Example 2: Get the virtual network configuration of the current Azure subscription and save it to a local file
```
PS C:\>Get-AzureVNetConfig -ExportToFile "c:\temp\MyAzNets.netcfg"
```

This command gets the virtual network configuration of the current Azure subscription and then saves it to a local file.

## PARAMETERS

### -ExportToFile
Specifies the path and file name of a network configuration file to be created from the settings.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureSMProfile
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
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

[Get-AzureVNetSite](.\Get-AzureVNetSite.md)

[Remove-AzureVNetConfig](.\Remove-AzureVNetConfig.md)

[Set-AzureVNetConfig](.\Set-AzureVNetConfig.md)

