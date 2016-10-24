---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: 6e1d094c-7bfb-41a8-96f1-30dd93891e87
schema: 2.0.0
ms.assetid: 05928D39-F461-4009-9AD7-D14FC00D1F9B
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Remove-AzureRmVirtualNetworkSubnetConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Remove-AzureRmVirtualNetworkSubnetConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureRmVirtualNetworkSubnetConfig

## SYNOPSIS
Removes a subnet configuration from a virtual network.

## SYNTAX

```
Remove-AzureRmVirtualNetworkSubnetConfig [-Name <String>] -VirtualNetwork <PSVirtualNetwork>
 [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmVirtualNetworkSubnetConfig** cmdlet removes a subnet from an Azure virtual network.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Name
Specifies the name of the subnet configuration to remove.

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

### -VirtualNetwork
Specifies the **VirtualNetwork** object that contains the subnet configuration to remove.

```yaml
Type: PSVirtualNetwork
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
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

[Add-AzureRmVirtualNetworkSubnetConfig](.\Add-AzureRmVirtualNetworkSubnetConfig.md)

[Get-AzureRmVirtualNetworkSubnetConfig](.\Get-AzureRmVirtualNetworkSubnetConfig.md)

[New-AzureRmVirtualNetworkSubnetConfig](.\New-AzureRmVirtualNetworkSubnetConfig.md)

[Set-AzureRmVirtualNetworkSubnetConfig](.\Set-AzureRmVirtualNetworkSubnetConfig.md)


