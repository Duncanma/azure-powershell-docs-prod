---
external help file: Microsoft.Azure.Commands.Batch.dll-Help.xml
online version: ef0b5395-55f2-4de8-970c-81685a4731e2
schema: 2.0.0
ms.assetid: 04070FDE-1880-467A-8360-1B44FB6B1271
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v2.2.0/Disable-AzureBatchAutoScale.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v2.2.0/Disable-AzureBatchAutoScale.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Disable-AzureBatchAutoScale

## SYNOPSIS
Disables automatic scaling of a pool.

## SYNTAX

```
Disable-AzureBatchAutoScale [-Id] <String> -BatchContext <BatchAccountContext> [<CommonParameters>]
```

## DESCRIPTION
The **Disable-AzureBatchAutoScale** cmdlet disables automatic scaling of the specified pool.

## EXAMPLES

### Example 1: Disable automatic scaling of a pool
```
PS C:\>Disable-AzureBatchAutoScale -Id "MyPool" -BatchContext $Context
```

This command disables automatic scaling for the pool named MyPool.

## PARAMETERS

### -BatchContext
Specifies the **BatchAccountContext** instance that this cmdlet uses to interact with the Batch service.
To obtain a **BatchAccountContext** object that contains access keys for your subscription, use the Get-AzureRmBatchAccountKeys cmdlet.

```yaml
Type: BatchAccountContext
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Id
Specifies the object ID of the pool.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Enable-AzureBatchAutoScale](.\Enable-AzureBatchAutoScale.md)

[Test-AzureBatchAutoScale](.\Test-AzureBatchAutoScale.md)

[Azure Batch Cmdlets](.\AzureRM.Batch.md)


