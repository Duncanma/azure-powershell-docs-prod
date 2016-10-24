---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: b9b7992c-fa0f-4a0b-9c1c-8b46ac78de8f
schema: 2.0.0
ms.assetid: 26B285C2-8841-48E9-8FD3-16DAC8DCD9C4
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Get-AzureRmApplicationGatewayUrlPathMapConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/Get-AzureRmApplicationGatewayUrlPathMapConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmApplicationGatewayUrlPathMapConfig

## SYNOPSIS
Gets an array of URL path mappings to a backend server pool.

## SYNTAX

```
Get-AzureRmApplicationGatewayUrlPathMapConfig [-Name <String>] -ApplicationGateway <PSApplicationGateway>
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmApplicationGatewayURLPathMapConfig** cmdlet gets an array of URL path mappings to a backend server pool.

## EXAMPLES

### Example 1: Get a URL path map configuration
```
PS C:\>Get-AzureRmApplicationGatewayUrlPathMapConfig -ApplicationGateway Gateway
```

This command gets the URL path map configurations from the backend server located on the application gateway named Gateway.

## PARAMETERS

### -Name
Specifies the URL path map name in which this cmdlet get the path map configuration.

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

### -ApplicationGateway
Specifies the application gateway to which this cmdlet gets a URL path map configuration.

```yaml
Type: PSApplicationGateway
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

[Add-AzureRmApplicationGatewayUrlPathMapConfig](.\Add-AzureRmApplicationGatewayUrlPathMapConfig.md)

[New-AzureRmApplicationGatewayUrlPathMapConfig](.\New-AzureRmApplicationGatewayUrlPathMapConfig.md)

[Remove-AzureRmApplicationGatewayUrlPathMapConfig](.\Remove-AzureRmApplicationGatewayUrlPathMapConfig.md)

[Set-AzureRmApplicationGatewayUrlPathMapConfig](.\Set-AzureRmApplicationGatewayUrlPathMapConfig.md)


