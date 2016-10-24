---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: f6cfc61b-9164-4392-aab0-6e3411509434
schema: 2.0.0
ms.assetid: 97BFE694-3EDA-47CC-9276-515A3269806C
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/Remove-AzureVMImageOSDiskConfig.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/Remove-AzureVMImageOSDiskConfig.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureVMImageOSDiskConfig

## SYNOPSIS
Removes the operating system disk configuration from the DiskConfigSet object.

## SYNTAX

```
Remove-AzureVMImageOSDiskConfig [-DiskConfig] <VirtualMachineImageDiskConfigSet> [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureVMImageOSDiskConfig** cmdlet removes the operating system disk configuration from the DiskConfigSet object.

## EXAMPLES

### Example 1: Remove the operating system disk configuration from a DiskConfigSet
```
PS C:\> $Disk = New-AzureDiskConfigSet
PS C:\> $Disk = Set-AzureOSDiskConfig -DiskConfig $Disk -HostCaching ReadWrite
PS C:\> Remove-AzureVMImageOSDiskConfig -DiskConfig $Disk
```

This command removes the operating system disk configuration from the DiskConfigSet object

## PARAMETERS

### -DiskConfig
Specifies the disk configuration object that encapsulates the operating system disk and Data Disk objects.

```yaml
Type: VirtualMachineImageDiskConfigSet
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.WindowsAzure.Commands.ServiceManagement.Model.VirtualMachineImageDiskConfigSet

## NOTES

## RELATED LINKS

[Set-AzureVMImageOSDiskConfig](.\Set-AzureVMImageOSDiskConfig.md)


