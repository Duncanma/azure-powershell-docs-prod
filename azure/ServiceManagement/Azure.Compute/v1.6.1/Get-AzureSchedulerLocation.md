---
external help file: Microsoft.WindowsAzure.Commands.dll-Help.xml
online version: .\Get-AzureSchedulerJob.md
schema: 2.0.0
ms.assetid: 7CB1A0D0-7D9C-4273-963E-F92A5D132711
updated_at: 10/19/2016 9:46 PM
ms.date: 10/19/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.6.1/Get-AzureSchedulerLocation.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/74b346742ae40ec75fc505ce886fae2812ab9a3a/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.6.1/Get-AzureSchedulerLocation.md
ms.topic: reference
ms.prod: powershell
ms.service: azure-powershell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureSchedulerLocation

## SYNOPSIS
Gets available scheduler locations.

## SYNTAX

```
Get-AzureSchedulerLocation [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
powershell_prelim

The **Get-AzureSchedulerLocation** cmdlet gets available scheduler locations.

## EXAMPLES

### Example 1: Get available scheduler locations
```
PS C:\>Get-AzureSchedulerLocation
```

This command gets available scheduler locations.

## PARAMETERS

### -Profile
In-memory profile.```yaml
Type: AzureSMProfile
Parameter Sets: (All)
Aliases: 

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

[Get-AzureSchedulerJob](.\Get-AzureSchedulerJob.md)

[Get-AzureSchedulerJobCollection](.\Get-AzureSchedulerJobCollection.md)

[Get-AzureSchedulerJobHistory](.\Get-AzureSchedulerJobHistory.md)

