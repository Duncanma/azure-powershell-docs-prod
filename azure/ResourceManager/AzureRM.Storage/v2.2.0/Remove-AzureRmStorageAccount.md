---
external help file: Microsoft.Azure.Commands.Management.Storage.dll-Help.xml
online version: e6a13f25-4565-4ab1-8690-a292c89c9c43
schema: 2.0.0
ms.assetid: FB551EA5-4159-4D77-8733-025AE66A13AF
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Storage/v2.2.0/Remove-AzureRmStorageAccount.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Storage/v2.2.0/Remove-AzureRmStorageAccount.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureRmStorageAccount

## SYNOPSIS
Removes a Storage account from Azure.

## SYNTAX

```
Remove-AzureRmStorageAccount [-ResourceGroupName] <String> [-Name] <String> [-Force] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmStorageAccount** cmdlet removes a Storage account from Azure.

## EXAMPLES

### Example 1: Remove a Storage account
```
PS C:\>Remove-AzureRmStorageAccount -ResourceGroupName "RG01" -AccountName "MyStorageAccount"
```

This command removes the specified Storage account.

## PARAMETERS

### -ResourceGroupName
Specifies the name of the resource group that contains the Storage account to remove.

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

### -Name
Specifies the name of the Storage account to remove.

```yaml
Type: String
Parameter Sets: (All)
Aliases: StorageAccountName, AccountName

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Force
@{Text=}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureRmStorageAccount](.\Get-AzureRmStorageAccount.md)

[New-AzureRmStorageAccount](.\New-AzureRmStorageAccount.md)

[Set-AzureRmStorageAccount](.\Set-AzureRmStorageAccount.md)


