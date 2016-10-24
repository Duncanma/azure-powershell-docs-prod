---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: 12e991fe-45c2-48c6-af0f-738d93021e5c
schema: 2.0.0
ms.assetid: 3DE861AD-5A86-4C36-911C-EB695DAC1CF2
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Remove-AzureVNetGateway.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Remove-AzureVNetGateway.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureVNetGateway

## SYNOPSIS
Deletes a VPN gateway.

## SYNTAX

```
Remove-AzureVNetGateway [-VNetName] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureVNetGateway** cmdlet deletes an existing virtual private network (VPN) gateway for a virtual network.

## EXAMPLES

### Example 1: Remove a virtual network gateway
```
PS C:\>Remove-AzureVNetGateway -VNetName "ContosoVN07"
```

This command removes the virtual network gateway from the virtual network named ContosoVN07.

## PARAMETERS

### -VNetName
Specifies the virtual network in which this cmdlet deletes the VPN gateway.

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

[Get-AzureVNetGateway](.\Get-AzureVNetGateway.md)

[New-AzureVNetGateway](.\New-AzureVNetGateway.md)

[Reset-AzureVNetGateway](.\Reset-AzureVNetGateway.md)

[Resize-AzureVNetGateway](.\Resize-AzureVNetGateway.md)

[Set-AzureVNetGatewayKey](.\Set-AzureVNetGatewayKey.md)


