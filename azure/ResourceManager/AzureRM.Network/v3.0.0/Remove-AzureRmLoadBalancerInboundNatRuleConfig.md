---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: c408960e-1598-4476-90c7-d0abd6f03b80
schema: 2.0.0
ms.assetid: 1B122BBC-6CE6-4E13-918B-E9F0C93F6DE0
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Remove-AzureRmLoadBalancerInboundNatRuleConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Remove-AzureRmLoadBalancerInboundNatRuleConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureRmLoadBalancerInboundNatRuleConfig

## SYNOPSIS
Removes an inbound NAT rule configuration from a load balancer.

## SYNTAX

```
Remove-AzureRmLoadBalancerInboundNatRuleConfig [-Name <String>] -LoadBalancer <PSLoadBalancer>
 [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmLoadBalancerInboundNatRuleConfig** cmdlet removes an inbound network address translation (NAT) rule configuration from an Azure load balancer.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Name
Specifies the name of the inbound NAT rule configuration that this cmdlet removes.

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

### -LoadBalancer
Specifies the **LoadBalancer** object that contains the inbound NAT rule configuration that this cmdlet removes.

```yaml
Type: PSLoadBalancer
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

[Add-AzureRmLoadBalancerInboundNatRuleConfig](.\Add-AzureRmLoadBalancerInboundNatRuleConfig.md)

[Get-AzureRmLoadBalancerInboundNatRuleConfig](.\Get-AzureRmLoadBalancerInboundNatRuleConfig.md)

[New-AzureRmLoadBalancerInboundNatRuleConfig](.\New-AzureRmLoadBalancerInboundNatRuleConfig.md)

[Set-AzureRmLoadBalancerInboundNatRuleConfig](.\Set-AzureRmLoadBalancerInboundNatRuleConfig.md)


