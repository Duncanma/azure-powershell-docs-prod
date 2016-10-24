---
external help file: Microsoft.Azure.Commands.ApiManagement.ServiceManagement.dll-Help.xml
online version: 45b96ab0-ace3-4754-b162-88027ac8ca41
schema: 2.0.0
ms.assetid: 8B0116E5-0AED-4050-BF11-1BFE65DB9436
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/Microsoft.Azure.Commands.ApiManagement.ServiceManagement/v2.2.0/Get-AzureRmApiManagementAuthorizationServer.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/Microsoft.Azure.Commands.ApiManagement.ServiceManagement/v2.2.0/Get-AzureRmApiManagementAuthorizationServer.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmApiManagementAuthorizationServer

## SYNOPSIS
Gets an API Management authorization server.

## SYNTAX

### Get all authorization server (Default)
```
Get-AzureRmApiManagementAuthorizationServer -Context <PsApiManagementContext> [<CommonParameters>]
```

### Get by Id
```
Get-AzureRmApiManagementAuthorizationServer -Context <PsApiManagementContext> [-ServerId <String>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmApiManagementAuthorizationServer** cmdlet gets all Azure API Management authorization servers or specified authorization servers.

## EXAMPLES

### Example 1: Get all authorization servers
```
PS C:\>Get-AzureRmApiManagementAuthrizarionServer -Context $ApiMgmtContext
```

This command gets all API Management authorization servers.

### Example 2: Get a specified authorization server
```
PS C:\>Get-AzureRmApiManagementCertificate -Context $ApiMgmtContext -ServerId "0123456789"
```

This command gets the specified authorization server.

## PARAMETERS

### -Context
@{Text=}

```yaml
Type: PsApiManagementContext
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ServerId
@{Text=}

```yaml
Type: String
Parameter Sets: Get by Id
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### IList<Microsoft.Azure.Commands.ApiManagement.ServiceManagement.Models.PsApiManagementOAuth2AuthrozationServer>

## NOTES

## RELATED LINKS

[New-AzureRmApiManagementAuthorizationServer](.\New-AzureRmApiManagementAuthorizationServer.md)

[Remove-AzureRmApiManagementAuthorizationServer](.\Remove-AzureRmApiManagementAuthorizationServer.md)

[Set-AzureRmApiManagementAuthorizationServer](.\Set-AzureRmApiManagementAuthorizationServer.md)


