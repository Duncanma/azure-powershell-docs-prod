---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: cbde7141-7332-4884-a0f9-2e5d3a4d76bd
schema: 2.0.0
ms.assetid: 4FD915D4-C8AD-486E-9162-A6EC3864D7E6
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/Get-AzureInternalLoadBalancer.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/Get-AzureInternalLoadBalancer.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureInternalLoadBalancer

## SYNOPSIS
Gets the details of the internal load balancer configuration.

## SYNTAX

```
Get-AzureInternalLoadBalancer [-ServiceName] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureInternalLoadBalancer** cmdlet gets the details of the internal load balancer configuration for an Azure service.

## EXAMPLES

### Example 1: Get details for an internal load balancer
```
PS C:\>Get-AzureService -ServiceName "ContosoService" | Get-AzureInternalLoadBalancer
```

This command gets the service named ContosoService by using the Get-AzureService cmdlet.
The command passes that service to the current cmdlet by using the pipeline operator.
The current cmdlet gets details for the internal load balancer for that service.

## PARAMETERS

### -ServiceName
Specifies the name of the service for which this cmdlet gets details for an internal load balancer.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureSMProfile
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

### Microsoft.WindowsAzure.Commands.ServiceManagement.Model.InternalLoadBalancerContext

## NOTES

## RELATED LINKS

[Add-AzureInternalLoadBalancer](.\Add-AzureInternalLoadBalancer.md)

[Get-AzureService](.\Get-AzureService.md)

[New-AzureInternalLoadBalancerConfig](.\New-AzureInternalLoadBalancerConfig.md)

[Remove-AzureInternalLoadBalancer](.\Remove-AzureInternalLoadBalancer.md)

[Set-AzureInternalLoadBalancer](.\Set-AzureInternalLoadBalancer.md)


