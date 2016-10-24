---
external help file: Microsoft.Azure.Commands.OperationalInsights.dll-Help.xml
online version: 3a46bcd5-ad81-411a-92aa-7788ebd2473e
schema: 2.0.0
ms.assetid: 61CF7249-4D3B-4655-99A9-97CDA93ECAE9
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.OperationalInsights/v2.2.0/Get-AzureRmOperationalInsightsWorkspace.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.OperationalInsights/v2.2.0/Get-AzureRmOperationalInsightsWorkspace.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmOperationalInsightsWorkspace

## SYNOPSIS
Gets information about a workspace.

## SYNTAX

```
Get-AzureRmOperationalInsightsWorkspace [[-ResourceGroupName] <String>] [[-Name] <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmOperationalInsightsWorkspace** cmdlet gets information about an existing workspace.
If you specify a workspace name, this cmdlet gets information about that workspace.
If you do not specify a name, this cmdlet gets information about all workspaces in a resource group.
If you do not specify a name and resource group, this cmdlet gets information about all workspaces in a subscription.

## EXAMPLES

### Example 1: Get a workspace by name
```
PS C:\>Get-AzureRmOperationalInsightsWorkspace  ¢â‚¬"Name "MyWorkspace"  ¢â‚¬"ResourceGroupName "ContosoResourceGroup"
```

This command gets a workspace named MyWorkspace in the resource group named ContosoResourceGroup.

## PARAMETERS

### -ResourceGroupName
Specifies the name of an Azure resource group.

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

### -Name
Specifies the workspace name.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Azure Operational Insights Cmdlets](.\AzureRM.OperationalInsights.md)


