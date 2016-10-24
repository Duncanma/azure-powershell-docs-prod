---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: c408960e-1598-4476-90c7-d0abd6f03b80
schema: 2.0.0
ms.assetid: 46D3ABB2-E5D1-464C-A261-EEC749BC89A8
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/New-AzureRmLoadBalancerInboundNatRuleConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/New-AzureRmLoadBalancerInboundNatRuleConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureRmLoadBalancerInboundNatRuleConfig

## SYNOPSIS
Creates an inbound NAT rule configuration for a load balancer.

## SYNTAX

### SetByResourceId
```
New-AzureRmLoadBalancerInboundNatRuleConfig -Name <String> [-FrontendIpConfigurationId <String>]
 [-Protocol <String>] [-FrontendPort <Int32>] [-BackendPort <Int32>] [-IdleTimeoutInMinutes <Int32>]
 [-EnableFloatingIP] [<CommonParameters>]
```

### SetByResource
```
New-AzureRmLoadBalancerInboundNatRuleConfig -Name <String>
 [-FrontendIpConfiguration <PSFrontendIPConfiguration>] [-Protocol <String>] [-FrontendPort <Int32>]
 [-BackendPort <Int32>] [-IdleTimeoutInMinutes <Int32>] [-EnableFloatingIP] [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRmLoadBalancerInboundNatRuleConfig** cmdlet creates an inbound network address translation (NAT) rule configuration for an Azure load balancer.

## EXAMPLES

### Example 1: Create an inbound NAT rule configuration for a load balancer
```
PS C:\>$publicip = New-AzureRmPublicIpAddress -ResourceGroupName "MyResourceGroup" -Name "MyPublicIP" -Location "West US" -AllocationMethod "Dynamic"
PS C:\> $frontend = New-AzureRmLoadBalancerFrontendIpConfig -Name "FrontendIpConfig01" -PublicIpAddress $publicip
PS C:\> New-AzureRmLoadBalancerInboundNatRuleConfig -Name "MyInboundNatRule" -FrontendIPConfiguration $frontend -Protocol "Tcp" -FrontendPort 3389 -BackendPort 3389
```

The first command creates a public IP address named MyPublicIP in the resource group named MyResourceGroup, and then stores it in the $publicip variable.

The second command creates a front-end IP configuration named FrontendIpConfig01 using the public IP address in $publicip, and then stores it in the $frontend variable.

The third command creates an inbound NAT rule configuration named MyInboundNatRule using the front-end object in $frontend.
The TCP protocol is specified and the front-end port is 3389, the same as the backend port in this case.
The *FrontendIpConfiguration*, *Procotol*, *FrontendPort*, and *BackendPort* parameters are all required to create an inbound NAT rule configuration.

## PARAMETERS

### -Name
Specifies the name of the rule configuration that this cmdlet creates.

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

### -FrontendIpConfigurationId
Specifies the ID for a front-end IP address configuration.

```yaml
Type: String
Parameter Sets: SetByResourceId
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Protocol
Specifies a protocol.
The acceptable values for this parameter are:

- Tcp
- Udp

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

### -FrontendPort
Specifies the front-end port that is matched by a load balancer rule configuration.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BackendPort
Specifies the backend port for traffic that is matched by this rule configuration.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IdleTimeoutInMinutes
Specifies the length of time, in minutes, for which the state of conversations is maintained in a load balancer.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnableFloatingIP
Indicates that this cmdlet enables a floating IP address for a rule configuration.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FrontendIpConfiguration
Specifies a list of front-end IP addresses to associate with a load balancer rule configuration.

```yaml
Type: PSFrontendIPConfiguration
Parameter Sets: SetByResource
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

[Add-AzureRmLoadBalancerInboundNatRuleConfig](.\Add-AzureRmLoadBalancerInboundNatRuleConfig.md)

[Get-AzureRmLoadBalancerInboundNatRuleConfig](.\Get-AzureRmLoadBalancerInboundNatRuleConfig.md)

[New-AzureRmLoadBalancerFrontendIpConfig](.\New-AzureRmLoadBalancerFrontendIpConfig.md)

[New-AzureRmPublicIpAddress](.\New-AzureRmPublicIpAddress.md)

[Remove-AzureRmLoadBalancerInboundNatRuleConfig](.\Remove-AzureRmLoadBalancerInboundNatRuleConfig.md)

[Set-AzureRmLoadBalancerInboundNatRuleConfig](.\Set-AzureRmLoadBalancerInboundNatRuleConfig.md)


