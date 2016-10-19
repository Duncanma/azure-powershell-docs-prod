---
external help file: Microsoft.Azure.Commands.Websites.dll-Help.xml
online version: .\New-AzureRmAppServicePlan.md
schema: 2.0.0
ms.assetid: 472D30E3-A03C-4BDE-B0FA-0C582AB8D88F
updated_at: 10/18/2016 9:38 PM
ms.date: 10/18/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Websites/v1.0/Get-AzureRmAppServicePlan.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/23cdb8705d4ab9807c0e21b238f3b134a7d49c7d/azureps-cmdlets-docs/ResourceManager/AzureRM.Websites/v1.0/Get-AzureRmAppServicePlan.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmAppServicePlan

## SYNOPSIS
Gets an azure_2 App Service plan in the specified resource group.

## SYNTAX

### S1
```
Get-AzureRmAppServicePlan [[-ResourceGroupName] <String>] [[-Name] <String>] [<CommonParameters>]
```

### S2
```
Get-AzureRmAppServicePlan [-Location] <String> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmAppServicePlan** cmdlet gets an azure_2 App Service plan in the specified resource group.

## EXAMPLES

### Example 1: Get an App Service plan from a resource group
```
PS C:\>Get-AzureRmAppServicePlan -ResourceGroupName "Default-Web-WestUS" -Name "ContosoAppServPlan"
```

This command gets the App Service plan named ContosoAppServPlan that belongs to the resource group named Default-Web-WestUS.

## PARAMETERS

### -ResourceGroupName
@{Text=}

```yaml
Type: String
Parameter Sets: S1
Aliases: 

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
@{Text=}

```yaml
Type: String
Parameter Sets: S1
Aliases: 

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Location
@{Text=}

```yaml
Type: String
Parameter Sets: S2
Aliases: 

Required: True
Position: 0
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

[New-AzureRmAppServicePlan](.\New-AzureRmAppServicePlan.md)

[Remove-AzureRmAppServicePlan](.\Remove-AzureRmAppServicePlan.md)

[Set-AzureRmAppServicePlan](.\Set-AzureRmAppServicePlan.md)


