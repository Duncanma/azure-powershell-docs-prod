---
external help file: Microsoft.Azure.Commands.Scheduler.dll-Help.xml
online version: 5d156d67-eb59-4f91-a44a-b74fdfa44414
schema: 2.0.0
ms.assetid: 5D736BE1-7F64-4431-974F-3D77B029F959
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Scheduler/v0.11.0/Get-AzureRmSchedulerJobCollection.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Scheduler/v0.11.0/Get-AzureRmSchedulerJobCollection.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmSchedulerJobCollection

## SYNOPSIS
Gets job collections.

## SYNTAX

```
Get-AzureRmSchedulerJobCollection [-ResourceGroupName <String>] [-JobCollectionName <String>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmSchedulerJobCollection** cmdlet gets job collections in Azure Scheduler.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ResourceGroupName
Specifies resource group from which this cmdlet gets job collections.

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

### -JobCollectionName
Specifies the name of a job collection.

```yaml
Type: String
Parameter Sets: (All)
Aliases: Name, ResourceName

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

## NOTES

## RELATED LINKS

[Disable-AzureRmSchedulerJobCollection](.\Disable-AzureRmSchedulerJobCollection.md)

[Enable-AzureRmSchedulerJobCollection](.\Enable-AzureRmSchedulerJobCollection.md)

[New-AzureRmSchedulerJobCollection](.\New-AzureRmSchedulerJobCollection.md)

[Remove-AzureRmSchedulerJobCollection](.\Remove-AzureRmSchedulerJobCollection.md)

[Set-AzureRmSchedulerJobCollection](.\Set-AzureRmSchedulerJobCollection.md)


