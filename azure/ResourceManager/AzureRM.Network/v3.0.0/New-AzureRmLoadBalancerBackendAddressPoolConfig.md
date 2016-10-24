---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: 62bc19a9-1a5a-4aa3-ba6d-a2fc3124c8b7
schema: 2.0.0
ms.assetid: 91FDBECA-D66F-4243-8E08-4E6D04CADBDF
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/New-AzureRmLoadBalancerBackendAddressPoolConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/New-AzureRmLoadBalancerBackendAddressPoolConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureRmLoadBalancerBackendAddressPoolConfig

## SYNOPSIS
Creates a backend address pool configuration for a load balancer.

## SYNTAX

```
New-AzureRmLoadBalancerBackendAddressPoolConfig -Name <String> [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRmLoadBalancerBackendAddressPoolConfig** cmdlet creates a backend address pool configuration for an Azure load balancer.

## EXAMPLES

### Example 1: Create a backend address pool configuration for a load balancer
```
PS C:\>New-AzureRmLoadBalancerBackendAddressPoolConfig -Name "BackendAddressPool02"
```

This command creates a backend address pool configuration named BackendAddressPool02 for a load balancer.

## PARAMETERS

### -Name
Specifies the name of the address pool configuration to create.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Add-AzureRmLoadBalancerBackendAddressPoolConfig](.\Add-AzureRmLoadBalancerBackendAddressPoolConfig.md)

[Get-AzureRmLoadBalancerBackendAddressPoolConfig](.\Get-AzureRmLoadBalancerBackendAddressPoolConfig.md)

[Remove-AzureRmLoadBalancerBackendAddressPoolConfig](.\Remove-AzureRmLoadBalancerBackendAddressPoolConfig.md)


