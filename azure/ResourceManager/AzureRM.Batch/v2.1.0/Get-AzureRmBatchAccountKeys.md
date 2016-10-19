---
external help file: Microsoft.Azure.Commands.Batch.dll-Help.xml
online version: .\New-AzureRmBatchAccountKey.md
schema: 2.0.0
ms.assetid: A8A9A07E-1A67-405A-891E-71CDBCDD6C7E
updated_at: 10/18/2016 9:38 PM
ms.date: 10/18/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v2.1.0/Get-AzureRmBatchAccountKeys.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/23cdb8705d4ab9807c0e21b238f3b134a7d49c7d/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v2.1.0/Get-AzureRmBatchAccountKeys.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmBatchAccountKeys

## SYNOPSIS
Gets the keys of a Batch account.

## SYNTAX

```
Get-AzureRmBatchAccountKeys [-AccountName] <String> [-ResourceGroupName <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmBatchAccountKeys** cmdlet gets the keys of an Azure Batch account in the current subscription.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -AccountName
Specifies the name of the account for which this cmdlet gets keys.

```yaml
Type: String
Parameter Sets: (All)
Aliases: Name

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group that contains the account for which this cmdlet gets keys.

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

## NOTES

## RELATED LINKS

[New-AzureRmBatchAccountKey](.\New-AzureRmBatchAccountKey.md)

[Azure Batch Cmdlets](.\AzureRM.Batch.md)


