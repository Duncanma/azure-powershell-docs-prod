---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: f1a7d04f-cc24-4855-aedc-d07fc93e032f
schema: 2.0.0
ms.assetid: 5E7FEDFE-B1DB-472D-B6D7-63BBFCE199DD
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Get-AzureRmLoadBalancer.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Get-AzureRmLoadBalancer.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmLoadBalancer

## SYNOPSIS
Gets a load balancer.

## SYNTAX

### NoExpand
```
Get-AzureRmLoadBalancer [-Name <String>] [-ResourceGroupName <String>] [<CommonParameters>]
```

### Expand
```
Get-AzureRmLoadBalancer -Name <String> -ResourceGroupName <String> -ExpandResource <String>
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmLoadBalancer** cmdlet gets one or more Azure load balancers that are contained in a resource group.

## EXAMPLES

### Example 1: Get a load balancer
```
PS C:\>Get-AzureRmLoadBalancer -Name "MyLoadBalancer" -ResourceGroupName "MyResourceGroup"
```

This command gets the load balancer named MyLoadBalancer.
A load balancer must exist before you can run this cmdlet.

## PARAMETERS

### -Name
@{Text=}

```yaml
Type: String
Parameter Sets: NoExpand
Aliases: ResourceName

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

```yaml
Type: String
Parameter Sets: Expand
Aliases: ResourceName

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
@{Text=}

```yaml
Type: String
Parameter Sets: NoExpand
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

```yaml
Type: String
Parameter Sets: Expand
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ExpandResource
@{Text=}

```yaml
Type: String
Parameter Sets: Expand
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[New-AzureRmLoadBalancer](.\New-AzureRmLoadBalancer.md)

[Remove-AzureRmLoadBalancer](.\Remove-AzureRmLoadBalancer.md)

[Set-AzureRmLoadBalancer](.\Set-AzureRmLoadBalancer.md)


