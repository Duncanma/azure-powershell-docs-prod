---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: 48b9d59d-ff51-4f70-9a29-fd017a9a8383
schema: 2.0.0
ms.assetid: C2A3C653-FBBA-4D24-BCED-FAEA67C1D4A6
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Reset-AzureVirtualNetworkGatewayKey.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Reset-AzureVirtualNetworkGatewayKey.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Reset-AzureVirtualNetworkGatewayKey

## SYNOPSIS
Resets a virtual network gateway key.

## SYNTAX

```
Reset-AzureVirtualNetworkGatewayKey [-GatewayId] <String> [-ConnectedEntityId] <String> [-keyLength] <Int32>
 [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Reset-AzureVirtualNetworkGatewayKey** cmdlet resets a virtual network gateway key.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ConnectedEntityId
Specifies the ID of a connected entity.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GatewayId
Specifies the ID of a gateway.

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

### -keyLength
Specifies the key length.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
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

[Get-AzureVirtualNetworkGatewayKey](.\Get-AzureVirtualNetworkGatewayKey.md)

[Set-AzureVirtualNetworkGatewayKey](.\Set-AzureVirtualNetworkGatewayKey.md)


