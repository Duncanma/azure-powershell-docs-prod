---
external help file: Microsoft.Azure.Commands.Network.dll-Help.xml
online version: 4f097539-a581-468e-ac68-67095b88204b
schema: 2.0.0
ms.assetid: FB6C852A-7B15-4E8E-A3DC-62B8881250CF
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/New-AzureRmApplicationGatewayAuthenticationCertificate.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Network/v3.0.0/New-AzureRmApplicationGatewayAuthenticationCertificate.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureRmApplicationGatewayAuthenticationCertificate

## SYNOPSIS
Creates an authentication certificate for an application gateway.

## SYNTAX

```
New-AzureRmApplicationGatewayAuthenticationCertificate -Name <String> -CertificateFile <String> [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRmApplicationGatewayAuthenticationCertificate** cmdlet creates an authentication certificate for an Azure application gateway.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Name
Specifies a name for the authentication certificate.

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

### -CertificateFile
Specifies the path of the authentication certificate.

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

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.String

## OUTPUTS

### Microsoft.Azure.Commands.Network.Models.PSApplicationGatewayAuthenticationCertificate

## NOTES
* Keywords: azure, azurerm, arm, resource, management, manager, network, networking

## RELATED LINKS

[Add-AzureRmApplicationGatewayAuthenticationCertificate](.\Add-AzureRmApplicationGatewayAuthenticationCertificate.md)

[Get-AzureRmApplicationGatewayAuthenticationCertificate](.\Get-AzureRmApplicationGatewayAuthenticationCertificate.md)

[Remove-AzureRmApplicationGatewayAuthenticationCertificate](.\Remove-AzureRmApplicationGatewayAuthenticationCertificate.md)

[Set-AzureRmApplicationGatewayAuthenticationCertificate](.\Set-AzureRmApplicationGatewayAuthenticationCertificate.md)


