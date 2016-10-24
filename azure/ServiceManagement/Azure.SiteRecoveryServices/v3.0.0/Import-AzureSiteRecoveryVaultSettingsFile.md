---
external help file: Microsoft.Azure.Commands.RecoveryServicesRdfe.dll-Help.xml
online version: 7e20a21f-e0e3-452c-8960-62e279062134
schema: 2.0.0
ms.assetid: BC42AAB9-738F-4EB9-90F3-9AD054075927
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.SiteRecoveryServices/v3.0.0/Import-AzureSiteRecoveryVaultSettingsFile.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.SiteRecoveryServices/v3.0.0/Import-AzureSiteRecoveryVaultSettingsFile.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Import-AzureSiteRecoveryVaultSettingsFile

## SYNOPSIS
Imports a Site Recovery vault settings file.

## SYNTAX

```
Import-AzureSiteRecoveryVaultSettingsFile [-Path] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Import-AzureSiteRecoveryVaultSettingsFile** cmdlet imports an Azure Site Recovery vault settings file to set the vault context for subsequent Site Recovery operations in the current session.

## EXAMPLES

### Example 1: Import a vault settings file
```
PS C:\>Import-AzureSiteRecoveryVaultSettingsFile -Path "C:\Users\Contoso\Contosovault Monday, October 6, 2014.VaultCredentials"
VERBOSE: Vault Settings File path: C:\Users\Contoso\Contosovault Monday, October 6, 2014.VaultCredentials

ResourceName                                                CloudServiceName
------------                                                ----------------
Contosovault                                                RecoveryServices-6JP23WE3SKKOM5AFQG2YQAI22MNOWK52QDKWMUP...
```

This command imports the vault settings file at the specified path.

## PARAMETERS

### -Path
Specifies the path of the Site Recovery vault settings file.
This file can be downloaded from the Site Recovery vault portal and stored locally.

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

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

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

## NOTES

## RELATED LINKS

[Get-AzureSiteRecoveryVaultSettings](.\Get-AzureSiteRecoveryVaultSettings.md)

[Get-AzureSiteRecoveryVaultSettingsFile](.\Get-AzureSiteRecoveryVaultSettingsFile.md)


