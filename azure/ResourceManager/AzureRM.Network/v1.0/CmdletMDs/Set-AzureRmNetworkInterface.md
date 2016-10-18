---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: .\Get-AzureRmNetworkInterface.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0/CmdletMDs/Set-AzureRmNetworkInterface.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0/CmdletMDs/Set-AzureRmNetworkInterface.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Set-AzureRmNetworkInterface

## SYNOPSIS
Sets the goal state for a network interface.

## SYNTAX

```
Set-AzureRmNetworkInterface -NetworkInterface <PSNetworkInterface> [-InformationAction <ActionPreference>]
 [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureRmNetworkInterface** sets the goal state for an azure_2 network interface.

## EXAMPLES

### Example 1: Configure a network interface
```
PS C:\>$Nic = Get-AzureRmNetworkInterface -ResourceGroupName "ResourceGroup1" -Name "NetworkInterface1"
PS C:\> $Nic.IpConfigurations[0].PrivateIpAddress = "10.0.1.20"
PS C:\> $Nic.IpConfigurations[0].PrivateIpAllocationMethod = "Static"
PS C:\> $Nic.Tag = @{Name = "Name"; Value = "Value"}
PS C:\> Set-AzureRmNetworkInterface -NetworkInterface $Nic
```

This example configures a network interface.
The first command creates a network interface named NetworkInterface1 in resource group ResourceGroup1.

The second command sets the private IP address of the IP configuration.

The third command sets the private IP allocation method to Static.

The fourth command sets a tag on the network interface.

The fifth command uses the information stored in the $Nic variable to set the network interface.

## PARAMETERS

### -NetworkInterface
Specifies a **NetworkInterface** object that represents the goal state for a network interface.

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

### -InformationAction
@{Text=}```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
@{Text=}```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

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

[Get-AzureRmNetworkInterface](.\Get-AzureRmNetworkInterface.md)

[Get-AzureRmNetworkInterface](.\Get-AzureRmNetworkInterface.md)

[New-AzureRmNetworkInterface](.\New-AzureRmNetworkInterface.md)

[Remove-AzureRmNetworkInterface](.\Remove-AzureRmNetworkInterface.md)
