---
external help file: Microsoft.Azure.Commands.Media.dll-Help.xml
online version: .\Get-AzureRmMediaService.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Media/CmdletMDs/Get-AzureRmMediaServiceNameAvailability.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ResourceManager/AzureRM.Media/CmdletMDs/Get-AzureRmMediaServiceNameAvailability.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmMediaServiceNameAvailability

## SYNOPSIS
Checks whether a media service name is available.
Media service names are globally unique.

## SYNTAX

```
Get-AzureRmMediaServiceNameAvailability [-AccountName] <String> [-InformationAction <ActionPreference>]
 [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmMediaServiceNameAvailability** cmdlet checks whether a media service name is available.
Media service names are globally unique.

## EXAMPLES

### Example 1: Check whether a Media Service name is available
```
PS C:\>Get-AzureRmMediaServiceNameAvailability -AccountName "MediaService1"
```

This command checks if the name MediaService1 is available.

## PARAMETERS

### -AccountName
Specifies the name of the media service that this cmdlet gets.

```yaml
Type: String
Parameter Sets: (All)
Aliases: Name, ResourceName

Required: True
Position: 0
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

[Get-AzureRmMediaService](.\Get-AzureRmMediaService.md)

[New-AzureRmMediaService](.\New-AzureRmMediaService.md)

[Remove-AzureRmMediaService](.\Remove-AzureRmMediaService.md)

[Set-AzureRmMediaService](.\Set-AzureRmMediaService.md)

