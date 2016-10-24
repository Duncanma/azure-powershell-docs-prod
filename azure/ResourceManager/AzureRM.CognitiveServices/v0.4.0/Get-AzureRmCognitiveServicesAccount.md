---
external help file: Microsoft.Azure.Commands.Management.CognitiveServices.dll-Help.xml
online version: e4e4cf67-fc15-4f16-9a5f-d8cb4a327631
schema: 2.0.0
ms.assetid: 30956A48-EAE8-41C4-A309-7CCAE10611D0
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.CognitiveServices/v0.4.0/Get-AzureRmCognitiveServicesAccount.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.CognitiveServices/v0.4.0/Get-AzureRmCognitiveServicesAccount.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmCognitiveServicesAccount

## SYNOPSIS
Gets an account.

## SYNTAX

### AccountNameParameterSet
```
Get-AzureRmCognitiveServicesAccount [-ResourceGroupName] <String> [-Name] <String> [<CommonParameters>]
```

### ResourceGroupParameterSet
```
Get-AzureRmCognitiveServicesAccount [[-ResourceGroupName] <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmCognitiveServicesAccount** cmdlet gets the provisioned Cognitive Services accounts in the resource group specified by the *ResoureGroupName* parameter.

If you do not specify the *ResoureGroupName* parameter, this cmdlet gets all Cognitive Services accounts for the current subscription.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ResourceGroupName
Specifies the name of the resource group the Cognitive Services account is assigned to.

```yaml
Type: String
Parameter Sets: AccountNameParameterSet
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

```yaml
Type: String
Parameter Sets: ResourceGroupParameterSet
Aliases: 

Required: False
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
Specifies the name of the Cognitive Services account to get.

```yaml
Type: String
Parameter Sets: AccountNameParameterSet
Aliases: CognitiveServicesAccountName, AccountName

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

[New-AzureRmCognitiveServicesAccount](.\New-AzureRmCognitiveServicesAccount.md)

[Remove-AzureRmCognitiveServicesAccount](.\Remove-AzureRmCognitiveServicesAccount.md)

[Set-AzureRmCognitiveServicesAccount](.\Set-AzureRmCognitiveServicesAccount.md)


