---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: .\Get-AzureStorageAccount.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v0.9.8/CmdletMDs/Get-AzureStorageKey.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v0.9.8/CmdletMDs/Get-AzureStorageKey.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Get-AzureStorageKey

## SYNOPSIS
Returns the primary and secondary storage account keys for an Azure storage account.

## SYNTAX

```
Get-AzureStorageKey [-StorageAccountName] <String> [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureStorageKey** cmdlet returns an object with the Azure Storage account name, the primary account key, and the secondary account key of the specified Azure storage account as properties.

## EXAMPLES

### Example 1: Get an object that contains primary and secondary storage keys
```
PS C:\>Get-AzureStorageKey -StorageAccountName "ContosoStore01"
```

This command gets an object with the primary and secondary storage keys for the ContosoStore01 storage account.

### Example 2: Get the primary storage account key and store it in a variable
```
PS C:\>$ContosoStoreKey = (Get-AzureStorageKey -StorageAccountName "ContosoStore01").Primary
```

This command puts the primary storage account key for the ContosoStore01 storage account in the $ContosoStoreKey variable.

## PARAMETERS

### -StorageAccountName
Specifies the storage account name.

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
Type: AzureProfile
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
* To get help with Node.js, use the `help node-dev` command. For help with PHP extensions, use the `help php-dev` command.

## RELATED LINKS

[Get-AzureStorageAccount](.\Get-AzureStorageAccount.md)

[New-AzureStorageAccount](.\New-AzureStorageAccount.md)

[New-AzureStorageKey](.\New-AzureStorageKey.md)

[Remove-AzureStorageAccount](.\Remove-AzureStorageAccount.md)

[Set-AzureStorageAccount](.\Set-AzureStorageAccount.md)
