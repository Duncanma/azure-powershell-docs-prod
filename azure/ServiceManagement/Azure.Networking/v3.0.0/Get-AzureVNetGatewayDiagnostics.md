---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: dc5d95fa-d713-430f-8dd1-525c0401fbe6
schema: 2.0.0
ms.assetid: D6F05722-55C2-4419-9FF3-52F0874327B6
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Get-AzureVNetGatewayDiagnostics.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Get-AzureVNetGatewayDiagnostics.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureVNetGatewayDiagnostics

## SYNOPSIS
Gets the current state of diagnostics for a virtual network gateway.

## SYNTAX

```
Get-AzureVNetGatewayDiagnostics [-VNetName] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureVNetGatewayDiagnostics** cmdlet gets the current state of diagnostics for a virtual network gateway.
If a binary large object (blob) exists where the **Start-AzureVNetGatewayDiagnostics** saved a previous diagnostics session, this cmdlet also returns the URL of the blob where that cmdlet saved that diagnostics session.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -VNetName
Specifies the virtual network that contains a virtual network gateway for which this cmdlet gets diagnostics.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Profile
ps_azureprofile_description

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

## NOTES

## RELATED LINKS

[Start-AzureVNetGatewayDiagnostics](.\Start-AzureVNetGatewayDiagnostics.md)

[Stop-AzureVNetGatewayDiagnostics](.\Stop-AzureVNetGatewayDiagnostics.md)


