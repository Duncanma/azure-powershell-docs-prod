---
external help file: Microsoft.WindowsAzure.Commands.RemoteApp.dll-Help.xml
online version: 259e1176-0740-406e-948e-fd89693b563f
schema: 2.0.0
ms.assetid: ED191A06-0C1D-486E-91F3-3CB61AA470A6
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.RemoteApp/v3.0.0/Remove-AzureRemoteAppVNet.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.RemoteApp/v3.0.0/Remove-AzureRemoteAppVNet.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureRemoteAppVNet

## SYNOPSIS
Deletes an Azure RemoteApp virtual network.

## SYNTAX

```
Remove-AzureRemoteAppVNet -VNetName <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRemoteAppVNet** cmdlet deletes an Azure RemoteApp virtual network.

## EXAMPLES

### Example 1: Delete a specified virtual network
```
PS C:\>Remove-AzureRemoteAppVnet -VNetName "ContosoVNet"
```

This command deletes the virtual network named ContosoVNet

## PARAMETERS

### -VNetName
Specifies the name of the Azure RemoteApp virtual network to delete.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

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

[Get-AzureRemoteAppVNet](.\Get-AzureRemoteAppVNet.md)

[Set-AzureRemoteAppVNet](.\Set-AzureRemoteAppVNet.md)


