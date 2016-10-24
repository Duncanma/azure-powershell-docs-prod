---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: 34090e06-49fe-46db-9dc8-cf74006c9cef
schema: 2.0.0
ms.assetid: 9790AAD0-E2C7-4ABF-BAED-4EF0117AF10F
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/Get-AzureVMAccessExtension.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/Get-AzureVMAccessExtension.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureVMAccessExtension

## SYNOPSIS
Gets the VMAccess extension applied on a virtual machine.

## SYNTAX

```
Get-AzureVMAccessExtension -VM <IPersistentVM> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureVMAccessExtension** cmdlet gets the VMAccess extension applied on a virtual machine.

## EXAMPLES

### Example 1: Get the VMAccess extension for a virtual machine
```
PS C:\>Get-AzureVMAccessExtension -VM $VM;
```

This command gets the VMAccess extension for a virtual machine.

## PARAMETERS

### -VM
Specifies the persistent virtual machine object.

```yaml
Type: IPersistentVM
Parameter Sets: (All)
Aliases: InputObject

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
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

[Remove-AzureVMAccessExtension](.\Remove-AzureVMAccessExtension.md)

[Set-AzureVMAccessExtension](.\Set-AzureVMAccessExtension.md)


