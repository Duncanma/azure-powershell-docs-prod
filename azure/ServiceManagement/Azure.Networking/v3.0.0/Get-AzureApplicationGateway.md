---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: fd6f1d91-f019-4282-9f4f-46aeb4b4621b
schema: 2.0.0
ms.assetid: 75505BF1-69C2-4502-A161-F06527C20D34
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Get-AzureApplicationGateway.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Get-AzureApplicationGateway.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureApplicationGateway

## SYNOPSIS
Gets an Application Gateway.

## SYNTAX

```
Get-AzureApplicationGateway [[-Name] <String>] [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureApplicationGateway** cmdlet gets an existing azure_2 Application Gateway.

## EXAMPLES

### Example 1: Get an Application Gateway
```
PS C:\>Get-AzureApplicationGateway -Name "ApplicationGateway06"
```

This command gets the Application Gateway named ApplicationGateway06.

### Example 2: Get all Application Gateways
```
PS C:\>Get-AzureApplicationGateway
```

This command gets all the Application Gateways under your subscription.

## PARAMETERS

### -Name
Specifies the name of the Application Gateway that this cmdlet gets.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
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

### System.String

## OUTPUTS

### Microsoft.Azure.Networking.ApplicationGatewayObjectModel.ApplicationGateway, IEnumerable<Microsoft.Azure.Networking.ApplicationGatewayObjectModel.ApplicationGateway>

## NOTES

## RELATED LINKS

[New-AzureApplicationGateway](.\New-AzureApplicationGateway.md)

[Remove-AzureApplicationGateway](.\Remove-AzureApplicationGateway.md)

[Start-AzureApplicationGateway](.\Start-AzureApplicationGateway.md)

[Stop-AzureApplicationGateway](.\Stop-AzureApplicationGateway.md)

[Update-AzureApplicationGateway](.\Update-AzureApplicationGateway.md)


