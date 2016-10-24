---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: 893f28df-70ab-4aa5-8e87-ae1cd921a9ca
schema: 2.0.0
ms.assetid: EA9FBECA-A09F-478C-BDDE-851A937419AD
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Get-AzureApplicationGatewayConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v3.0.0/Get-AzureApplicationGatewayConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureApplicationGatewayConfig

## SYNOPSIS
Gets an Application Gateway configuration context.

## SYNTAX

```
Get-AzureApplicationGatewayConfig [-Name] <String> [-ExportToFile <String>] [-Profile <AzureSMProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureApplicationGatewayConfig** cmdlet gets an azure_2 Application Gateway configuration context.
A context includes both a configuration object and XML configuration.
You can save the XML configuration to a file.

## EXAMPLES

### Example 1: Get an Application Gateway configuration and save it to a file
```
PS C:\>Get-AzureApplicationGatewayConfig -Name "ApplicationGateway06" -ExportToFile "D:\config.xml"
```

This command gets the configuration for an Application Gateway named ApplicationGateway06.
The command saves it in the file in the specified path.

## PARAMETERS

### -Name
Specifies the name of the Application Gateway for which this cmdlet gets configuration information.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ExportToFile
Specifies a file path to which this cmdlet saves the configuration in XML format.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
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

### System.String

## OUTPUTS

### Microsoft.Azure.Networking.ApplicationGatewayObjectModel.ApplicationGatewayConfigContext

## NOTES

## RELATED LINKS

[Set-AzureApplicationGatewayConfig](.\Set-AzureApplicationGatewayConfig.md)


