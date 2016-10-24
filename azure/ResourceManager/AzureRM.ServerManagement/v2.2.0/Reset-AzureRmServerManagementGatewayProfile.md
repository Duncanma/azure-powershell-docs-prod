---
external help file: Microsoft.Azure.Commands.ServerManagement.dll-Help.xml
online version: 2a0a1a86-76a5-4e5d-8b9c-3284d1211e65
schema: 2.0.0
ms.assetid: 807E8C40-E28F-4CED-9753-D9A849DFBA08
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.ServerManagement/v2.2.0/Reset-AzureRmServerManagementGatewayProfile.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.ServerManagement/v2.2.0/Reset-AzureRmServerManagementGatewayProfile.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Reset-AzureRmServerManagementGatewayProfile

## SYNOPSIS
Resets the profile of a Server Management gateway.

## SYNTAX

### ByName
```
Reset-AzureRmServerManagementGatewayProfile [-ResourceGroupName] <String> [-GatewayName] <String>
 [<CommonParameters>]
```

### ByObject
```
Reset-AzureRmServerManagementGatewayProfile [-Gateway] <Gateway> [<CommonParameters>]
```

## DESCRIPTION
The **Reset-AzureRmServerManagementGatewayProfile** cmdlet resets the profile for an Azure Server Management Gateway.

You will need to use the Save-AzureRmServerManagementGatewayProfile cmdlet to download the profile and then the Install-AzureRmServerManagementGatewayProfile cmdlet to save it after you reset the profile.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ResourceGroupName
Specifies the name of the resource group that the gateway belongs to.

```yaml
Type: String
Parameter Sets: ByName
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -GatewayName
Specifies the name of the gateway for which the cmdlet resets the profile.

```yaml
Type: String
Parameter Sets: ByName
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Gateway
Specifies the gateway for which the cmdlet resets the profile for.

May be specified instead of ResourceGoupName and GatewayName

```yaml
Type: Gateway
Parameter Sets: ByObject
Aliases: 

Required: True
Position: 0
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

[Install-AzureRmServerManagementGatewayProfile](.\Install-AzureRmServerManagementGatewayProfile.md)

[Save-AzureRmServerManagementGatewayProfile](.\Save-AzureRmServerManagementGatewayProfile.md)


