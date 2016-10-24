---
external help file: Microsoft.Azure.Commands.OperationalInsights.dll-Help.xml
online version: 3a46bcd5-ad81-411a-92aa-7788ebd2473e
schema: 2.0.0
ms.assetid: BC39AA99-529A-412C-91BD-67DCD93F7113
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.OperationalInsights/v2.2.0/Get-AzureRmOperationalInsightsWorkspaceSharedKeys.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.OperationalInsights/v2.2.0/Get-AzureRmOperationalInsightsWorkspaceSharedKeys.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmOperationalInsightsWorkspaceSharedKeys

## SYNOPSIS
Gets the shared keys for a workspace.

## SYNTAX

```
Get-AzureRmOperationalInsightsWorkspaceSharedKeys [-ResourceGroupName] <String> [-Name] <String>
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmOperationalInsightsWorkspaceSharedKeys** cmdlet lists the shared keys for a workspace.
The keys are used to connect Operational Insights agents to the workspace.

## EXAMPLES

### Example 1: Get shared keys by workspace name
```
PS C:\>Get-AzureRmOperationalInsightsWorkspaceSharedKeys  ¢â‚¬"ResourceGroupName "ContosoResourceGroup"  ¢â‚¬"Name "MyWorkspace"
```

This command gets the shared keys for the workspace named MyWorkspace in the resource group named ContosoResourceGroup.

### Example 2: Get shared keys by using the pipeline
```
PS C:\>Get-AzureRmOperationalInsightsWorkspace  ¢â‚¬"ResourceGroupName "ContosoResourceGroup"  ¢â‚¬"Name "MyWorkspace" | Get-AzureRmOperationalInsightsWorkspaceSharedKeys
```

This command gets the workspace named MyWorkspace using the Get-AzureRmOperationalInsightsWorkspace cmdlet, and then passes the workspace to the **Get-AzureRmOperationalInsightsWorkspaceSharedKeys** cmdlet.
The command gets the shared keys for that workspace.

## PARAMETERS

### -ResourceGroupName
Specifies the name of an Azure resource group.

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

### -Name
Specifies the workspace name.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
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

[Get-AzureRmOperationalInsightsWorkspace](.\Get-AzureRmOperationalInsightsWorkspace.md)


