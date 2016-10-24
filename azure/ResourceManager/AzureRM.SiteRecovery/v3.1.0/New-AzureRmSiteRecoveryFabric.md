---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
online version: 481af120-a656-40d5-833c-95f1be8e4ffb
schema: 2.0.0
ms.assetid: EBD805F3-40EA-459D-8B9B-A3FD16FF6808
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v3.1.0/New-AzureRmSiteRecoveryFabric.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v3.1.0/New-AzureRmSiteRecoveryFabric.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureRmSiteRecoveryFabric

## SYNOPSIS
Creates an Azure Site Recovery Fabric.

## SYNTAX

```
New-AzureRmSiteRecoveryFabric -Name <String> [-Type <String>] [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRmSiteRecoveryFabric** cmdlet creates an Azure Site Recovery Fabric of the specified type.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Name
Specifies the name of the Azure Site Recovery Fabric

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Type
Specifies the Azure Site Recovery Fabric Type.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.Commands.SiteRecovery.ASRJob

## NOTES

## RELATED LINKS

[Get-AzureRmSiteRecoveryFabric](.\Get-AzureRmSiteRecoveryFabric.md)

[Remove-AzureRmSiteRecoveryFabric](.\Remove-AzureRmSiteRecoveryFabric.md)


