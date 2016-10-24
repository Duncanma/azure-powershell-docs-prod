---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
online version: 7962d734-1c67-4085-91fc-6a9c9d99ad8b
schema: 2.0.0
ms.assetid: 2D551F2C-5DFE-42FC-BF3C-D34776C0892B
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v3.1.0/Get-AzureRmSiteRecoveryVM.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v3.1.0/Get-AzureRmSiteRecoveryVM.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmSiteRecoveryVM

## SYNOPSIS
Gets information about Site Recovery-managed virtual machines.

## SYNTAX

### ByObject (Default)
```
Get-AzureRmSiteRecoveryVM -ProtectionContainer <ASRProtectionContainer> [<CommonParameters>]
```

### ByObjectWithName
```
Get-AzureRmSiteRecoveryVM -Name <String> -ProtectionContainer <ASRProtectionContainer> [<CommonParameters>]
```

### ByObjectWithFriendlyName
```
Get-AzureRmSiteRecoveryVM -FriendlyName <String> -ProtectionContainer <ASRProtectionContainer>
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmSiteRecoveryVM** cmdlet gets information about virtual machines managed in Azure Site Recovery.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ProtectionContainer
Specifies the Site Recovery protection container object.

```yaml
Type: ASRProtectionContainer
Parameter Sets: ByObject
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

```yaml
Type: ASRProtectionContainer
Parameter Sets: ByObjectWithName, ByObjectWithFriendlyName
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Name
Specifies the name of the virtual machine.

```yaml
Type: String
Parameter Sets: ByObjectWithName
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FriendlyName
Specifies the friendly name of the virtual machine.

```yaml
Type: String
Parameter Sets: ByObjectWithFriendlyName
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

[Set-AzureRmSiteRecoveryVM](.\Set-AzureRmSiteRecoveryVM.md)


