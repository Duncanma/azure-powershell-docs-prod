---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
online version: .\Restart-AzureRmSiteRecoveryJob.md
schema: 2.0.0
ms.assetid: 874C0981-749B-4161-9AC2-AC445A72EBEB
updated_at: 10/18/2016 9:38 PM
ms.date: 10/18/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v2.1.0/Get-AzureRmSiteRecoveryJob.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/23cdb8705d4ab9807c0e21b238f3b134a7d49c7d/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v2.1.0/Get-AzureRmSiteRecoveryJob.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmSiteRecoveryJob

## SYNOPSIS
Gets the operation information for the current Site Recovery vault.

## SYNTAX

### ByParam (Default)
```
Get-AzureRmSiteRecoveryJob [-StartTime <DateTime>] [-EndTime <DateTime>] [-TargetObjectId <String>]
 [-State <String>] [<CommonParameters>]
```

### ByName
```
Get-AzureRmSiteRecoveryJob -Name <String> [<CommonParameters>]
```

### ByObject
```
Get-AzureRmSiteRecoveryJob -Job <ASRJob> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmSiteRecoveryJob** cmdlet gets Azure Site Recovery jobs.
You can use this cmdlet to view the operation information for the current Site Recovery vault.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -EndTime
Specifies the end time for the jobs.
This cmdlet gets all jobs that started before the specified time.
To obtain a **DateTime** object for this parameter, use the Get-Date cmdlet.
For more information, type `Get-Help Get-Date`.

```yaml
Type: DateTime
Parameter Sets: ByParam
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Job
Specifies the Site Recovery job.

```yaml
Type: ASRJob
Parameter Sets: ByObject
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Name
Specifies a unique name that identifies the job.

```yaml
Type: String
Parameter Sets: ByName
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StartTime
Specifies the start time for the jobs.
This cmdlet gets all jobs that started after the specified time.

```yaml
Type: DateTime
Parameter Sets: ByParam
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -State
Specifies the input state for a Site Recovery job.
This cmdlet gets all jobs that match the specified state.
The acceptable values for this parameter are:

- NotStarted
- InProgress
- Succeeded
- Other
- Failed
- Cancelled
- Suspended

```yaml
Type: String
Parameter Sets: ByParam
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TargetObjectId
Specifies the ID of the object targeted by the job.

```yaml
Type: String
Parameter Sets: ByParam
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

[Restart-AzureRmSiteRecoveryJob](.\Restart-AzureRmSiteRecoveryJob.md)

[Resume-AzureRmSiteRecoveryJob](.\Resume-AzureRmSiteRecoveryJob.md)

[Stop-AzureRmSiteRecoveryJob](.\Stop-AzureRmSiteRecoveryJob.md)


