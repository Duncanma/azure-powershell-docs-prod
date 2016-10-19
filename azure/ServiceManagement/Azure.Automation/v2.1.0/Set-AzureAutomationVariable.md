---
external help file: Microsoft.Azure.Commands.Automation.dll-Help.xml
online version: .\Get-AzureAutomationVariable.md
schema: 2.0.0
ms.assetid: 91FDC595-CF88-47F2-A6A4-D155665D8857
updated_at: 10/18/2016 9:38 PM
ms.date: 10/18/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Automation/v2.1.0/Set-AzureAutomationVariable.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/23cdb8705d4ab9807c0e21b238f3b134a7d49c7d/azureps-cmdlets-docs/ServiceManagement/Azure.Automation/v2.1.0/Set-AzureAutomationVariable.md
ms.topic: reference
ms.prod: powershell
ms.service: azure-powershell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Set-AzureAutomationVariable

## SYNOPSIS
Modifies an Automation variable.

## SYNTAX

### UpdateVariableDescription
```
Set-AzureAutomationVariable [-Name] <String> -Description <String> [-AutomationAccountName] <String>
 [-Profile <AzureSMProfile>] [<CommonParameters>]
```

### UpdateVariableValue
```
Set-AzureAutomationVariable [-Name] <String> -Encrypted <Boolean> -Value <Object>
 [-AutomationAccountName] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureAutomationVariable** cmdlet modifies the value or description of a variable in Microsoft Azure Automation.

## EXAMPLES

### Example 1: Set the value of a variable
```
PS C:\> Set-AzureAutomationVariable -AutomationAccountName "Contoso17" -Name "MyStringVariable" -Value "New Value" -Encrypted $False
```

This command sets a new value for the variable named MyStringVariable in the Azure Automation account named Contoso17.

## PARAMETERS

### -AutomationAccountName
@{Text=}

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

### -Description
@{Text=}

```yaml
Type: String
Parameter Sets: UpdateVariableDescription
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
@{Text=}

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Value
@{Text=}

```yaml
Type: Object
Parameter Sets: UpdateVariableValue
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Encrypted
@{Text=}

```yaml
Type: Boolean
Parameter Sets: UpdateVariableValue
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
@{Text=}

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

### Microsoft.Azure.Commands.Automation.Model.Variable

## NOTES

## RELATED LINKS

[Get-AzureAutomationVariable](.\Get-AzureAutomationVariable.md)

[New-AzureAutomationVariable](.\New-AzureAutomationVariable.md)

[Remove-AzureAutomationVariable](.\Remove-AzureAutomationVariable.md)

