---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: dd8dbd57-462f-426f-a03f-e6bac629d0d3
schema: 2.0.0
ms.assetid: 87FE577F-4470-4790-818D-5E77007DD965
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/Remove-AzureVMDiagnosticsExtension.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v3.0.0/Remove-AzureVMDiagnosticsExtension.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Remove-AzureVMDiagnosticsExtension

## SYNOPSIS
Removes the Azure Diagnostics extension from a virtual machine.

## SYNTAX

```
Remove-AzureVMDiagnosticsExtension -VM <IPersistentVM> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureVMDiagnosticsExtension** cmdlet removes a Microsoft Azure Diagnostics extension from a virtual machine.
You must pass the output of this cmdlet to the Update-AzureVM cmdlet.

## EXAMPLES

### Example 1: Remove the Azure Diagnostics extension from a virtual machine
```
PS C:\>Remove-AzureVMDiagnosticsExtension -VM $VM | Update-AzureVM
```

This command removes the Azure Diagnostics extension from a virtual machine.

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

[Get-AzureVMDiagnosticsExtension](.\Get-AzureVMDiagnosticsExtension.md)

[Set-AzureVMDiagnosticsExtension](.\Set-AzureVMDiagnosticsExtension.md)

[Update-AzureVM](.\Update-AzureVM.md)


