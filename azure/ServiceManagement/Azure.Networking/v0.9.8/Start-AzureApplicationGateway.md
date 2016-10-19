---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: .\Get-AzureApplicationGateway.md
schema: 2.0.0
ms.assetid: 9257F010-9013-4837-B648-A9053D6576A8
updated_at: 10/19/2016 10:11 PM
ms.date: 10/19/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v0.9.8/Start-AzureApplicationGateway.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/4b5e5bf2b9726cfa193914d0aa3066271dbb9e41/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v0.9.8/Start-AzureApplicationGateway.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Start-AzureApplicationGateway

## SYNOPSIS
Starts an application gateway.

## SYNTAX

```
Start-AzureApplicationGateway [-Name] <String> [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Start-AzureApplicationGateway** cmdlet starts an application gateway.

## EXAMPLES

### Example 1: Start an application gateway
```
PS C:\>Start-AzureApplicationGateway -Name "ApplicationGateway06"
```

This command starts the application gateway named ApplicationGateway06.

## PARAMETERS

### -Name
Specifies the name of the application gateway that this cmdlet starts.

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
Type: AzureProfile
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

### System.String

## OUTPUTS

### Microsoft.WindowsAzure.Management.ApplicationGateway.Models.ApplicationGatewayOperationResponse

## NOTES

## RELATED LINKS

[Get-AzureApplicationGateway](.\Get-AzureApplicationGateway.md)

[New-AzureApplicationGateway](.\New-AzureApplicationGateway.md)

[Remove-AzureApplicationGateway](.\Remove-AzureApplicationGateway.md)

[Stop-AzureApplicationGateway](.\Stop-AzureApplicationGateway.md)

[Update-AzureApplicationGateway](.\Update-AzureApplicationGateway.md)


