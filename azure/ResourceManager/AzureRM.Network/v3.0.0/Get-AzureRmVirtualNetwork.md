---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: 4f9ffaa1-0bc4-41c5-aa33-075bb5d09027
schema: 2.0.0
ms.assetid: 18C26932-AA29-4B7E-B47F-5E46C73D4580
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Get-AzureRmVirtualNetwork.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Get-AzureRmVirtualNetwork.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmVirtualNetwork

## SYNOPSIS
Gets a virtual network in a resource group.

## SYNTAX

### NoExpand
```
Get-AzureRmVirtualNetwork [-Name <String>] [-ResourceGroupName <String>] [<CommonParameters>]
```

### Expand
```
Get-AzureRmVirtualNetwork -Name <String> -ResourceGroupName <String> -ExpandResource <String>
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmVirtualNetwork** cmdlet gets one or more virtual networks n a resource group.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Name
Specifies the name of the virtual network that this cmdlet gets.

```yaml
Type: String
Parameter Sets: NoExpand
Aliases: ResourceName

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

```yaml
Type: String
Parameter Sets: Expand
Aliases: ResourceName

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group that virtual network belongs to.

```yaml
Type: String
Parameter Sets: NoExpand
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

```yaml
Type: String
Parameter Sets: Expand
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ExpandResource
@{Text=}

```yaml
Type: String
Parameter Sets: Expand
Aliases: 

Required: True
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

[New-AzureRmVirtualNetwork](.\New-AzureRmVirtualNetwork.md)

[Remove-AzureRmVirtualNetwork](.\Remove-AzureRmVirtualNetwork.md)

[Set-AzureRmVirtualNetwork](.\Set-AzureRmVirtualNetwork.md)


