---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: 6e190d23-9704-4bdf-8595-7f5946eb3d72
schema: 2.0.0
ms.assetid: 28CC3C65-E988-4BA4-BC96-79A2F6C36226
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/Remove-AzureStorageAccount.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/Remove-AzureStorageAccount.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureStorageAccount

## SYNOPSIS
Deletes the specified storage account from a subscription.

## SYNTAX

```
Remove-AzureStorageAccount [-StorageAccountName] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureStorageAccount** cmdlet removes an account from an Azure subscription.

## EXAMPLES

### Example 1: Remove a storage account
```
PS C:\>Remove-AzureStorageAccount -StorageAccountName "ContosoStore01"
```

This command removes the ContosoStore01 storage account from the specified subscription.

## PARAMETERS

### -StorageAccountName
Specifies the name of the storage account to remove.

```yaml
Type: String
Parameter Sets: (All)
Aliases: ServiceName

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
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

[Get-AzureStorageAccount](.\Get-AzureStorageAccount.md)

[New-AzureStorageAccount](.\New-AzureStorageAccount.md)

[Set-AzureStorageAccount](.\Set-AzureStorageAccount.md)


