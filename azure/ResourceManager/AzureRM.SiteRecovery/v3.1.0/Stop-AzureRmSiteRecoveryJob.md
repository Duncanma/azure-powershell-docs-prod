---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
online version: 874c0981-749b-4161-9ac2-ac445a72ebeb
schema: 2.0.0
ms.assetid: E6D258B8-6A3F-4C00-85B7-4E55F560333C
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v3.1.0/Stop-AzureRmSiteRecoveryJob.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v3.1.0/Stop-AzureRmSiteRecoveryJob.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Stop-AzureRmSiteRecoveryJob

## SYNOPSIS
Stops a Site Recovery job.

## SYNTAX

### ByObject (Default)
```
Stop-AzureRmSiteRecoveryJob -Job <ASRJob> [<CommonParameters>]
```

### ByName
```
Stop-AzureRmSiteRecoveryJob -Name <String> [<CommonParameters>]
```

## DESCRIPTION
The **Stop-AzureRmSiteRecoveryJob** cmdlet stops an Azure Site Recovery job.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Job
Specifies the Site Recovery job object to stop.

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
Specifies the unique name for the Site Recovery job to stop.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureRmSiteRecoveryJob](.\Get-AzureRmSiteRecoveryJob.md)

[Restart-AzureRmSiteRecoveryJob](.\Restart-AzureRmSiteRecoveryJob.md)

[Resume-AzureRmSiteRecoveryJob](.\Resume-AzureRmSiteRecoveryJob.md)


