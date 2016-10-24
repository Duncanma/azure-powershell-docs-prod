---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: 12e991fe-45c2-48c6-af0f-738d93021e5c
schema: 2.0.0
ms.assetid: E2145345-5413-4BA5-BDC5-7498213080C6
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Set-AzureVNetGateway.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Set-AzureVNetGateway.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Set-AzureVNetGateway

## SYNOPSIS
Enables or disables a VPN gateway for an azure_2 virtual network.

## SYNTAX

### Connect (Default)
```
Set-AzureVNetGateway [-Connect] [-VNetName] <String> [-LocalNetworkSiteName] <String>
 [-Profile <AzureSMProfile>] [<CommonParameters>]
```

### Disconnect
```
Set-AzureVNetGateway [-Disconnect] [-VNetName] <String> [-LocalNetworkSiteName] <String>
 [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureVNetGateway** cmdlet enables or disables a virtual private network (VPN) gateway for an azure_2 virtual network.
A virtual network gateway is a VPN endpoint for connecting to a virtual network.
Specify the *Connect* or *Disconnect* parameter to enable or disable the VPN connection between an on-premises local network site and a virtual network.

## EXAMPLES

### Example 1: Enable a virtual network gateway for a virtual network
```
PS C:\>Set-AzureVNetGateway -Connect -VnetName "ContosoProdNet" -LocalNetworkSiteName "ContosoBranchOffice"
```

This command enables the virtual network gateway between the azure_2 virtual network named ContosoProdNet and the VPN device for the local network site named ContosoBranchOffice.

### Example 2: Disable a virtual network gateway for a virtual network
```
PS C:\>Set-AzureVNetGateway -Disconnect -VnetName "ContosoProdNet" -LocalNetworkSiteName "ContosoBranchOffice"
```

This command disables the virtual network gateway between the azure_2 virtual network named ContosoProdNet and the VPN device for the local network site named ContosoBranchOffice.

## PARAMETERS

### -Connect
Indicates that this cmdlet enables the VPN connection between a virtual network and a local network site.

```yaml
Type: SwitchParameter
Parameter Sets: Connect
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -VNetName
Specifies the virtual network for which this cmdlet enables or disables the VPN connection.

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

### -LocalNetworkSiteName
Specifies the name of the on-premises local network site for which this cmdlet enables or disables the VPN connection.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Disconnect
Indicates that this cmdlet disables the VPN connection between a virtual network and a local network site.

```yaml
Type: SwitchParameter
Parameter Sets: Disconnect
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

[Remove-AzureVNetGateway](.\Remove-AzureVNetGateway.md)

[Reset-AzureVNetGateway](.\Reset-AzureVNetGateway.md)

[Resize-AzureVNetGateway](.\Resize-AzureVNetGateway.md)


