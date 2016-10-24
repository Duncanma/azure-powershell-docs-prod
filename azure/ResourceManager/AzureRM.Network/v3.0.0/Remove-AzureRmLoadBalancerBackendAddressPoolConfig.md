---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: 62bc19a9-1a5a-4aa3-ba6d-a2fc3124c8b7
schema: 2.0.0
ms.assetid: 7128E252-123D-4A37-A876-F645EB546810
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Remove-AzureRmLoadBalancerBackendAddressPoolConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Remove-AzureRmLoadBalancerBackendAddressPoolConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureRmLoadBalancerBackendAddressPoolConfig

## SYNOPSIS
Removes a backend address pool configuration from a load balancer.

## SYNTAX

```
Remove-AzureRmLoadBalancerBackendAddressPoolConfig [-Name <String>] -LoadBalancer <PSLoadBalancer>
 [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmLoadBalancerBackendAddressPoolConfig** cmdlet removes a backend address pool from a load balancer.

## EXAMPLES

### Example 1: Remove a backend address pool configuration from a load balancer
```
PS C:\>Get-AzureRmLoadBalancer -Name "MyLoadBalancer" -ResourceGroupName "MyResourceGroup" | Remove-AzureRmLoadBalancerBackendAddressPoolConfig -Name "BackendAddressPool02" | Set-AzureRmLoadBalancer
```

This command gets the load balancer named MyLoadBalancer and passes it to **Remove-AzureRmLoadBalancerBackendAddressPoolConfig**, which removes the BackendAddressPool02 configuration from MyLoadBalancer.
Finally, the Set-AzureRmLoadBalancer cmdlet updates MyLoadBalancer.
Note that a backend address pool configuration must exist before you can delete it.

## PARAMETERS

### -Name
Specifies the name of the backend address pool that this cmdlet removes.

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
Specifies the load balancer that contains the backend address pool to remove.

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

[Add-AzureRmLoadBalancerBackendAddressPoolConfig](.\Add-AzureRmLoadBalancerBackendAddressPoolConfig.md)

[Get-AzureRmLoadBalancer](.\Get-AzureRmLoadBalancer.md)

[Get-AzureRmLoadBalancerBackendAddressPoolConfig](.\Get-AzureRmLoadBalancerBackendAddressPoolConfig.md)

[New-AzureRmLoadBalancerBackendAddressPoolConfig](.\New-AzureRmLoadBalancerBackendAddressPoolConfig.md)


