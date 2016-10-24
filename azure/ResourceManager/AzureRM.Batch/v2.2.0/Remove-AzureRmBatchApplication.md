---
external help file: Microsoft.Azure.Commands.Batch.dll-Help.xml
online version: dd8f898f-99be-4b61-b4f6-1ae259d60dd9
schema: 2.0.0
ms.assetid: A0E1323E-BCA8-4907-B195-D13730628CDE
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v2.2.0/Remove-AzureRmBatchApplication.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Batch/v2.2.0/Remove-AzureRmBatchApplication.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureRmBatchApplication

## SYNOPSIS
Deletes an application from a Batch account.

## SYNTAX

```
Remove-AzureRmBatchApplication [-AccountName] <String> [-ResourceGroupName] <String> [-ApplicationId] <String>
 [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmBatchApplication** cmdlet deletes an application from an Azure Batch account.

## EXAMPLES

### Example 1: Delete an application from a Batch account
```
PS C:\>Remove-AzureRmBatchApplication -AccountName "ContosoBatch" -ResourceGroupName "ContosoBatchGroup" -ApplicationId "Litware"
```

This command deletes the Litware application from the ContosoBatch account.
The command fails if the application contains any packages.

## PARAMETERS

### -AccountName
Specifies the name of the Batch account from which this cmdlet removes an application.

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

### -ApplicationId
Specifies the ID of the application.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group that contains the Batch account.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureRmBatchApplication](.\Get-AzureRmBatchApplication.md)

[Get-AzureRmBatchApplicationPackage](.\Get-AzureRmBatchApplicationPackage.md)

[New-AzureRmBatchApplication](.\New-AzureRmBatchApplication.md)

[New-AzureRmBatchApplicationPackage](.\New-AzureRmBatchApplicationPackage.md)

[Remove-AzureRmBatchApplicationPackage](.\Remove-AzureRmBatchApplicationPackage.md)

[Set-AzureRmBatchApplication](.\Set-AzureRmBatchApplication.md)


