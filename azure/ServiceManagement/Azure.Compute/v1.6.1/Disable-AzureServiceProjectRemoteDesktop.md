---
external help file: Microsoft.WindowsAzure.Commands.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 848333F0-4687-4E7C-A775-1C6F148AA111
updated_at: 10/19/2016 9:46 PM
ms.date: 10/19/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.6.1/Disable-AzureServiceProjectRemoteDesktop.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/74b346742ae40ec75fc505ce886fae2812ab9a3a/azureps-cmdlets-docs/ServiceManagement/Azure.Compute/v1.6.1/Disable-AzureServiceProjectRemoteDesktop.md
ms.topic: reference
ms.prod: powershell
ms.service: azure-powershell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Disable-AzureServiceProjectRemoteDesktop

## SYNOPSIS
Disables Remote Desktop access to a cloud service.

## SYNTAX

```
Disable-AzureServiceProjectRemoteDesktop [-PassThru] [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
powershell_prelim

The **Disable-AzureServiceProjectRemoteDesktop** disables remote desktop access to a hosted service.
You must publish the service using the **Publish-AzureServiceProject** cmdlet after disabling Remote Desktop access for the change to take effect.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -PassThru
@{Text=}

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Profile
In-memory profile.```yaml
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

[Enable-AzureServiceProjectRemoteDesktop](.\Enable-AzureServiceProjectRemoteDesktop.md)

