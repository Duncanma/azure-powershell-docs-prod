---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: .\New-AzureVM.md
schema: 2.0.0
ms.assetid: BC52F5EE-C871-4D18-86F9-7D4684B45AF2
updated_at: 10/19/2016 10:11 PM
ms.date: 10/19/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v0.9.8/Get-AzureWinRMUri.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/4b5e5bf2b9726cfa193914d0aa3066271dbb9e41/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v0.9.8/Get-AzureWinRMUri.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureWinRMUri

## SYNOPSIS
Gets the URI to WinRM https listener to a virtual machine or a list of virtual machines in a hosted service.

## SYNTAX

```
Get-AzureWinRMUri [-ServiceName] <String> [[-Name] <String>] [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The Get-AzureWinRMUri cmdlet gets the URI of the Windows Remote Management (WinRM) https listener to a virtual machine or a list of virtual machines in a hosted service.

## EXAMPLES

### Example 1: Get the URI of the WinRM https listener to a virtual machine
```
PS C:\>Get-AzureWinRMUri -ServiceName MyService -Name MyVM
```

This command gets the UIR of the WinRM https listener to a virtual machine.

### Example 2: Get the URI of the WinRM https listener to a virtual machine of a specific service
```
PS C:\>Get-AzureWinRMUri -ServiceName MyService
```

This command gets the UIR of the WinRM https listener to a virtual machine.

## PARAMETERS

### -ServiceName
Specifies the name of the Microsoft Azure service that hosts the virtual machine.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
Specifies the name of the virtual machine to which the WinRM URI is generated.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureProfile
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

[New-AzureVM](.\New-AzureVM.md)

[New-AzureQuickVM](.\New-AzureQuickVM.md)


