---
external help file: Microsoft.Azure.Commands.RecoveryServices.ARM.dll-Help.xml
online version: .\Get-AzureRmRecoveryServicesVault.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.RecoveryServices/v2.0/CmdletMDs/New-AzureRmRecoveryServicesVault.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ResourceManager/AzureRM.RecoveryServices/v2.0/CmdletMDs/New-AzureRmRecoveryServicesVault.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureRmRecoveryServicesVault

## SYNOPSIS
Creates a new Recovery Services vault.

## SYNTAX

```
New-AzureRmRecoveryServicesVault -Name <String> -ResourceGroupName <String> -Location <String>
 [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRmRecoveryServicesVault** cmdlet creates a new Recovery Services vault.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Location
Specifies the name of the geographic location of the vault.

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

### -Name
Specifies the name of the vault to create.

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

### -ResourceGroupName
Specifies the name of the Azure resource group in which to create or from which to retrieve the specified Recovery Services object.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureRmRecoveryServicesVault](.\Get-AzureRmRecoveryServicesVault.md)

[Get-AzureRmRecoveryServicesVaultSettingsFile](.\Get-AzureRmRecoveryServicesVaultSettingsFile.md)

[Remove-AzureRmRecoveryServicesVault](.\Remove-AzureRmRecoveryServicesVault.md)

