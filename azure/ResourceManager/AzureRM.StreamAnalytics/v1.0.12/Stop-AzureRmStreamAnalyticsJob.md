---
external help file: Microsoft.Azure.Commands.StreamAnalytics.dll-Help.xml
online version: .\Get-AzureRmStreamAnalyticsJob.md
schema: 2.0.0
ms.assetid: F30CA3C3-D6CD-4FAA-9FD4-6E1D8A250785
updated_at: 10/18/2016 9:38 PM
ms.date: 10/18/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.StreamAnalytics/v1.0.12/Stop-AzureRmStreamAnalyticsJob.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/23cdb8705d4ab9807c0e21b238f3b134a7d49c7d/azureps-cmdlets-docs/ResourceManager/AzureRM.StreamAnalytics/v1.0.12/Stop-AzureRmStreamAnalyticsJob.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Stop-AzureRmStreamAnalyticsJob

## SYNOPSIS
Stops a Stream Analytics job.

## SYNTAX

```
Stop-AzureRmStreamAnalyticsJob [-Name] <String> [-ResourceGroupName] <String> [-PipelineVariable <String>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Stop-AzureRmStreamAnalyticsJob** cmdlet asynchronously stops a Stream Analytics job from running in azure_2 and deallocates resources that were that were being used.
The job definition and metadata remain available within your subscription through both the azure_2 Portal and Management APIs, such that the job can be edited and restarted.
You will not be charged for a job in the Stopped state.

## EXAMPLES

### EXAMPLE 1: Stop a running job
```
PS C:\>Stop-AzureRmStreamAnalyticsJob -ResourceGroupName "StreamAnalytics-Default-West-US" -Name "StreamingJob"
```

This command stops the job StreamingJob.

## PARAMETERS

### -Name
Specifies the name of the azure_2 Stream Analytics job to stop.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group to which the azure_2 Stream Analytics job belongs.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -PipelineVariable
Not Specified```yaml
Type: String
Parameter Sets: (All)
Aliases: pv

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

### System.Object

## NOTES

## RELATED LINKS

[Get-AzureRmStreamAnalyticsJob](.\Get-AzureRmStreamAnalyticsJob.md)

[Get-AzureRmStreamAnalyticsJob](.\Get-AzureRmStreamAnalyticsJob.md)

[New-AzureRmStreamAnalyticsJob](.\New-AzureRmStreamAnalyticsJob.md)

[Remove-AzureRmStreamAnalyticsJob](.\Remove-AzureRmStreamAnalyticsJob.md)

[Start-AzureRmStreamAnalyticsJob](.\Start-AzureRmStreamAnalyticsJob.md)


