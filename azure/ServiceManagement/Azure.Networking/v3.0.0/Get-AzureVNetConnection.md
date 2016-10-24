---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: acf3a543-1185-4fe7-9fa2-2fa5ea3b8ca2
schema: 2.0.0
ms.assetid: C3DA0104-9BFA-4FBF-A6C4-C3AE5C13D229
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Get-AzureVNetConnection.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Get-AzureVNetConnection.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureVNetConnection

## SYNOPSIS
Gets connections to an azure_2 virtual network.

## SYNTAX

```
Get-AzureVNetConnection [-VNetName] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureVNetConnection** cmdlet returns an object that specifies all active virtual private network (VPN) connections to an azure_2 virtual network.
VPN connections include cross premises site-to-site VPNs and virtual network to virtual network connections.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -VNetName
Specifies the name of the virtual network from which this cmdlet returns connections.

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


