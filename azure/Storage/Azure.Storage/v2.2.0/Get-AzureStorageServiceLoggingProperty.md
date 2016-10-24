---
external help file: Microsoft.WindowsAzure.Commands.Storage.dll-Help.xml
online version: .\New-AzureStorageContext.md
schema: 2.0.0
ms.assetid: 02217F39-6C93-401B-8801-52FDD38BA751
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/Storage/Azure.Storage/v2.2.0/Get-AzureStorageServiceLoggingProperty.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/Storage/Azure.Storage/v2.2.0/Get-AzureStorageServiceLoggingProperty.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureStorageServiceLoggingProperty

## SYNOPSIS
Gets logging properties for Azure Storage services.

## SYNTAX

```
Get-AzureStorageServiceLoggingProperty [-ServiceType] <StorageServiceType> [-Context <AzureStorageContext>]
 [-PipelineVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureStorageServiceLoggingProperty** cmdlet gets logging properties for Azure Storage services.

## EXAMPLES

### Example 1: Get logging properties for the Blob service
```
C:\PS>Get-AzureStorageServiceLoggingProperty -ServiceType Blob
```

This command gets logging properties for blob storage.

## PARAMETERS

### -ServiceType
Specifies the storage service type.
This cmdlet gets the logging properties for the service type that this parameter specifies.
The acceptable values for this parameter are:

- Blob 
- Table
- Queue
- File

The value of File is not currently supported.

```yaml
Type: StorageServiceType
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Context
Specifies an Azure storage context.
To obtain a storage context, use the New-AzureStorageContext cmdlet.

```yaml
Type: AzureStorageContext
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -PipelineVariable
@{Text=}

```yaml
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

## NOTES

## RELATED LINKS

[New-AzureStorageContext](.\New-AzureStorageContext.md)

[Set-AzureStorageServiceLoggingProperty](.\Set-AzureStorageServiceLoggingProperty.md)


