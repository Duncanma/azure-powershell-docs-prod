---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: .\Add-AzureLoadBalancerProbeConfig.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v0.9.8/CmdletMDs/New-AzureLoadBalancerProbeConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v0.9.8/CmdletMDs/New-AzureLoadBalancerProbeConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# New-AzureLoadBalancerProbeConfig

## SYNOPSIS
Creates a probe configuration for a load balancer.

## SYNTAX

```
New-AzureLoadBalancerProbeConfig -Name <String> [-RequestPath <String>] [-Protocol <String>] -Port <Int32>
 -IntervalInSeconds <Int32> -ProbeCount <Int32> [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureLoadBalancerProbeConfig** cmdlet creates a probe configuration for an Azure load balancer.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -IntervalInSeconds
Specifies the interval, in seconds, between probes to each instance of a load-balanced service.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
Specifies the name of the probe configuration to create.

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

### -Port
Specifies the port on which the new probe should connect to a load-balanced service.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProbeCount
Specifies the number of per-instance consecutive failures for an instance to be considered unhealthy.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Profile
Specifies an Azure profile.

```yaml
Type: AzureProfile
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Protocol
Specifies the protocol to use for the probe configuration.
The acceptable values for this parameter are:Tcp or Http.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 
Accepted values: Tcp, Http

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RequestPath
Specifies the path in a load-balanced service to probe to determine health.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Add-AzureLoadBalancerProbeConfig](.\Add-AzureLoadBalancerProbeConfig.md)

[Get-AzureLoadBalancerProbeConfig](.\Get-AzureLoadBalancerProbeConfig.md)

[Remove-AzureLoadBalancerProbeConfig](.\Remove-AzureLoadBalancerProbeConfig.md)

[Set-AzureLoadBalancerProbeConfig](.\Set-AzureLoadBalancerProbeConfig.md)
