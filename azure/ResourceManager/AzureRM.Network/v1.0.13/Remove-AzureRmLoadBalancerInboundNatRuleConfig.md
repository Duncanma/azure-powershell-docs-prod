---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: .\Add-AzureRmLoadBalancerInboundNatRuleConfig.md
schema: 2.0.0
ms.assetid: 1B122BBC-6CE6-4E13-918B-E9F0C93F6DE0
updated_at: 10/18/2016 9:38 PM
ms.date: 10/18/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0.13/Remove-AzureRmLoadBalancerInboundNatRuleConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/23cdb8705d4ab9807c0e21b238f3b134a7d49c7d/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v1.0.13/Remove-AzureRmLoadBalancerInboundNatRuleConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: azure-powershell
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
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmLoadBalancerInboundNatRuleConfig** cmdlet removes an inbound network address translation (NAT) rule configuration from an azure_2 load balancer.

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

[Add-AzureRmLoadBalancerInboundNatRuleConfig](.\Add-AzureRmLoadBalancerInboundNatRuleConfig.md)

[Get-AzureRmLoadBalancerInboundNatRuleConfig](.\Get-AzureRmLoadBalancerInboundNatRuleConfig.md)

[New-AzureRmLoadBalancerInboundNatRuleConfig](.\New-AzureRmLoadBalancerInboundNatRuleConfig.md)

[Set-AzureRmLoadBalancerInboundNatRuleConfig](.\Set-AzureRmLoadBalancerInboundNatRuleConfig.md)

