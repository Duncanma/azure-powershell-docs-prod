---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
online version: a1fe5285-5354-4e56-aed6-5e0446b07fa2
schema: 2.0.0
ms.assetid: 41F239D5-F201-495A-B68A-5A22228C9018
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v3.1.0/Get-AzureRmSiteRecoveryNetwork.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.SiteRecovery/v3.1.0/Get-AzureRmSiteRecoveryNetwork.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmSiteRecoveryNetwork

## SYNOPSIS
Gets information about the networks managed by Site Recovery for the current vault.

## SYNTAX

### Default (Default)
```
Get-AzureRmSiteRecoveryNetwork [<CommonParameters>]
```

### ByFriendlyNameLegacy
```
Get-AzureRmSiteRecoveryNetwork -Server <ASRServer> -FriendlyName <String> [<CommonParameters>]
```

### ByNameLegacy
```
Get-AzureRmSiteRecoveryNetwork -Server <ASRServer> -Name <String> [<CommonParameters>]
```

### ByServerObject
```
Get-AzureRmSiteRecoveryNetwork -Server <ASRServer> [<CommonParameters>]
```

### ByFriendlyName
```
Get-AzureRmSiteRecoveryNetwork -Fabric <ASRFabric> -FriendlyName <String> [<CommonParameters>]
```

### ByName
```
Get-AzureRmSiteRecoveryNetwork -Fabric <ASRFabric> -Name <String> [<CommonParameters>]
```

### ByFabricObject
```
Get-AzureRmSiteRecoveryNetwork -Fabric <ASRFabric> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmSiteRecoveryNetwork** cmdlet gets information about Azure Site Recovery networks for the current Azure Site Recovery vault.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Server
@{Text=}

```yaml
Type: ASRServer
Parameter Sets: ByFriendlyNameLegacy, ByNameLegacy, ByServerObject
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Name
Specifies the name of the virtual machine network.

```yaml
Type: String
Parameter Sets: ByNameLegacy
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

```yaml
Type: String
Parameter Sets: ByName
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -FriendlyName
Specifies the friendly name of the virtual machine network.

```yaml
Type: String
Parameter Sets: ByFriendlyNameLegacy
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

```yaml
Type: String
Parameter Sets: ByFriendlyName
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Fabric
@{Text=}

```yaml
Type: ASRFabric
Parameter Sets: ByFriendlyName, ByName, ByFabricObject
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS


