---
external help file: Microsoft.Azure.Commands.HDInsight.dll-Help.xml
online version: d1a5ef0f-aa03-41e5-aea5-da02d8aaf619
schema: 2.0.0
ms.assetid: C81AACA3-6EFA-4AEC-90FF-4CCEF4C07ECE
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.HDInsight/v2.2.0/Revoke-AzureRmHDInsightHttpServicesAccess.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.HDInsight/v2.2.0/Revoke-AzureRmHDInsightHttpServicesAccess.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Revoke-AzureRmHDInsightHttpServicesAccess

## SYNOPSIS
Disables HTTP access to the cluster.

## SYNTAX

```
Revoke-AzureRmHDInsightHttpServicesAccess [-ClusterName] <String> [-ResourceGroupName <String>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Revoke-AzureRmHDInsightHttpServicesAccess** cmdlet disables HTTP access to an Azure HDInsight cluster for ODBC, Ambari, Oozie and webHCatalog web services.

## EXAMPLES

### Example 1: Disable HTTP access to a cluster
```
PS C:\>Revoke-AzureRmHDInsightHttpServicesAccess `
       -ClusterName "your-hadoop_001"
```

This command revokes HTTP access to the cluster named your-hadoop_001.

## PARAMETERS

### -ClusterName
Specifies the name of the cluster.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group.

```yaml
Type: String
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

[Grant-AzureRmHDInsightHttpServicesAccess](.\Grant-AzureRmHDInsightHttpServicesAccess.md)


