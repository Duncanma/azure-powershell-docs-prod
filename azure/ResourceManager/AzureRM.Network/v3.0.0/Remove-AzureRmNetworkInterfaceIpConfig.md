---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: 50adaf9b-1426-4ae4-b21d-a4768f51020f
schema: 2.0.0
ms.assetid: 24176DC6-1A7C-4386-95AB-D393E7E041D4
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Remove-AzureRmNetworkInterfaceIpConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Remove-AzureRmNetworkInterfaceIpConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureRmNetworkInterfaceIpConfig

## SYNOPSIS
Removes a network interface IP configuration from a network interface.

## SYNTAX

```
Remove-AzureRmNetworkInterfaceIpConfig -Name <String> -NetworkInterface <PSNetworkInterface>
 [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmNetworkInterfaceIpConfig** cmdlet removes a network interface IP configuration from an Azure network interface.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Name
Specifies the name of the network interface IP configuration to remove.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NetworkInterface
Specifies a **NetworkInterface** object.
This object contains the network interface IP configuration to remove.

```yaml
Type: PSNetworkInterface
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
* Keywords: azure, azurerm, arm, resource, management, manager, network, networking

## RELATED LINKS

[Add-AzureRmNetworkInterfaceIpConfig](.\Add-AzureRmNetworkInterfaceIpConfig.md)

[Get-AzureRmNetworkInterfaceIpConfig](.\Get-AzureRmNetworkInterfaceIpConfig.md)

[New-AzureRmNetworkInterfaceIpConfig](.\New-AzureRmNetworkInterfaceIpConfig.md)

[Set-AzureRmNetworkInterfaceIpConfig](.\Set-AzureRmNetworkInterfaceIpConfig.md)


