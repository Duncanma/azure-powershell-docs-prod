---
external help file: Microsoft.WindowsAzure.Commands.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: AD7A9990-36D0-4AE5-82D8-8C0FAA159782
updated_at: 10/19/2016 9:46 PM
ms.date: 10/19/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.6.1/Show-AzurePortal.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/74b346742ae40ec75fc505ce886fae2812ab9a3a/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.6.1/Show-AzurePortal.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Show-AzurePortal

## SYNOPSIS
Show the Azure Management Portal.

## SYNTAX

```
Show-AzurePortal [[-Name] <String>] [-Realm <String>] [-Environment <String>] [-Profile <AzureSMProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
powershell_prelim

The **Show-AzurePortal** cmdlet shows the Azure Management Portal.

## EXAMPLES

### 1:
```
PS C:\>Show-AzurePortal -Name mySite
```

This example opens a browser on the Azure portal, showing information about a website named 'mySite'.

## PARAMETERS

### -Name
Specifies the name of the website to show in the portal.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Realm
Specifies the organization ID to use for federated authentication when displaying the Azure Portal.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Environment
The Microsoft Azure environment name to use```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
In-memory profile.```yaml
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

[Show-AzureWebsite](.\Show-AzureWebsite.md)


