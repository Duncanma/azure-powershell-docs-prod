---
external help file: Microsoft.Azure.Commands.DataLakeAnalytics.dll-Help.xml
online version: 006d22af-7a2a-45a1-bd38-35e1b750a7e5
schema: 2.0.0
ms.assetid: D59FA784-0339-4550-A114-7C86DDA39623
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.DataLakeAnalytics/v2.2.0/Get-AzureRmDataLakeAnalyticsCatalogItem.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.DataLakeAnalytics/v2.2.0/Get-AzureRmDataLakeAnalyticsCatalogItem.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmDataLakeAnalyticsCatalogItem

## SYNOPSIS
Gets a Data Lake Analytics catalog item or types of items.

## SYNTAX

```
Get-AzureRmDataLakeAnalyticsCatalogItem [-Account] <String> [-ItemType] <CatalogItemType>
 [[-Path] <CatalogPathInstance>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmDataLakeAnalyticsCatalogItem** gets a specified Azure Data Lake Analytics catalog item, or gets catalog items of a specified type.

## EXAMPLES

### Example 1: Get a specified database
```
PS C:\>Get-AzureRmDataLakeAnalyticsCatalogItem -Account "contosoadla" -ItemType Database -Path "databaseName"
```

This command gets the specified database.

### Example 2: Get tables in a specified database and schema
```
PS C:\>Get-AzureRmDataLakeAnalyticsDataSource -AccountName "contosoadla" -ItemType Table -Path "databaseName.schemaName"
```

This command gets a list of tables in the specified database.

## PARAMETERS

### -Account
Specifies the Data Lake Analytics account name.

```yaml
Type: String
Parameter Sets: (All)
Aliases: AccountName

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ItemType
Specifies the catalog item type of the item(s) being fetched or listed.
The acceptable values for this parameter are:

- Database
- Schema
- Assembly
- Table
- TableValuedFunction
- TableStatistics
- ExternalDataSource
- View
- Procedure
- Secret
- Credential

```yaml
Type: CatalogItemType
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Path
Specifies the multi-part path to the item to retrieve, or to the parent item of the items to list.
The parts of the path should be separated by a period (.).

```yaml
Type: CatalogPathInstance
Parameter Sets: (All)
Aliases: 

Required: False
Position: 2
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

[Test-AzureRmDataLakeAnalyticsCatalogItem](.\Test-AzureRmDataLakeAnalyticsCatalogItem.md)


