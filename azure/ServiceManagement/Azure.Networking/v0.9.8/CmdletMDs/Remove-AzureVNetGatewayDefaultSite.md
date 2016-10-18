---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: .\Set-AzureVNetGatewayDefaultSite.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v0.9.8/CmdletMDs/Remove-AzureVNetGatewayDefaultSite.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v0.9.8/CmdletMDs/Remove-AzureVNetGatewayDefaultSite.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureVNetGatewayDefaultSite

## SYNOPSIS
Removes the default route for forced tunneling traffic.

## SYNTAX

```
Remove-AzureVNetGatewayDefaultSite [-VNetName] <String> [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureVNetGatewayDefaultSite** cmdlet removes the default route to the on-premises site for forced tunneling traffic.
This cmdlet removes the route from an Azure virtual private network (VPN) gateway for a virtual network.

## EXAMPLES

### Example 1: Remove a route to the default site
```
PS C:\>Remove-AzureVNetGatewayDefaultSite -VnetName "ContosoVNet01"
```

This command removes the route to the default site from the VPN of the virtual network named ContosoVNet01.

## PARAMETERS

### -VNetName
Specifies a virtual network.
This cmdlet removes the default route from the VPN gateway for the virtual network that this parameter specifies.

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

## OUTPUTS

## NOTES

## RELATED LINKS

[Set-AzureVNetGatewayDefaultSite](.\Set-AzureVNetGatewayDefaultSite.md)

