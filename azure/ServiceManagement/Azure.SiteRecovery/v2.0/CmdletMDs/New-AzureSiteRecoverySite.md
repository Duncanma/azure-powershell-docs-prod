---
external help file: Microsoft.Azure.Commands.RecoveryServicesRdfe.dll-Help.xml
online version: .\Get-AzureSiteRecoverySite.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.SiteRecovery/v2.0/CmdletMDs/New-AzureSiteRecoverySite.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ServiceManagement/Azure.SiteRecovery/v2.0/CmdletMDs/New-AzureSiteRecoverySite.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureSiteRecoverySite

## SYNOPSIS
Creates an Azure Site Recovery site.

## SYNTAX

```
New-AzureSiteRecoverySite -Name <String> [-Vault <ASRVault>] [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureSiteRecoverySite** cmdlet creates an Azure Site Recovery site.

## EXAMPLES

### Example 1: Create a site recovery site
```
PS C:\>New-AzureSiteRecoverySite -Name "RecoverySite07"
```

This command creates a site recovery site named RecoverySite07.

## PARAMETERS

### -Name
Specifies a name for the site to create.

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

### -Profile
Specifies an Azure profile.

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

### -Vault
Specifies a vault for which to create the site.
To obtain an **ASRVault** object, use the **Get-AzureSiteRecoveryVault** cmdlet.

```yaml
Type: ASRVault
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

[Get-AzureSiteRecoverySite](.\Get-AzureSiteRecoverySite.md)

[Get-AzureSiteRecoveryVault](.\Get-AzureSiteRecoveryVault.md)

