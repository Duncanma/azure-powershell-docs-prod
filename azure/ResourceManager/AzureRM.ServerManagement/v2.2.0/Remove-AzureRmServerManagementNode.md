---
external help file: Microsoft.Azure.Commands.ServerManagement.dll-Help.xml
online version: 9123bd8a-e7dc-4905-9eea-df7654ab76bf
schema: 2.0.0
ms.assetid: 0DD93641-B6F3-4257-93E8-FCEEE16BF8F5
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.ServerManagement/v2.2.0/Remove-AzureRmServerManagementNode.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.ServerManagement/v2.2.0/Remove-AzureRmServerManagementNode.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureRmServerManagementNode

## SYNOPSIS
Removes a Server Management node.

## SYNTAX

### ByName
```
Remove-AzureRmServerManagementNode [-ResourceGroupName] <String> [-NodeName] <String> [<CommonParameters>]
```

### ByObject
```
Remove-AzureRmServerManagementNode [-Node] <Node> [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmServerManagementNode** cmdlet removes an Azure Server Management node.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ResourceGroupName
Specifies the name of the resource group that the node belongs to.

```yaml
Type: String
Parameter Sets: ByName
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -NodeName
Specifies the name of the node for which this cmdlet removes.

```yaml
Type: String
Parameter Sets: ByName
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Node
Specifies the node for which this cmdlet removes.

This parameter may be used instead of the *ResourceGroupName* and *NodeName* parameters.

```yaml
Type: Node
Parameter Sets: ByObject
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureRmServerManagementNode](.\Get-AzureRmServerManagementNode.md)

[New-AzureRmServerManagementNode](.\New-AzureRmServerManagementNode.md)


