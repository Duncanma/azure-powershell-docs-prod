---
external help file: Microsoft.WindowsAzure.Commands.RemoteApp.dll-Help.xml
online version: 8bba9407-770b-41a3-b516-3774518e5e10
schema: 2.0.0
ms.assetid: BC3CEB58-CE52-46C8-97A1-66CEA9098F8F
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.RemoteApp/v3.0.0/Get-AzureRemoteAppWorkspace.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.RemoteApp/v3.0.0/Get-AzureRemoteAppWorkspace.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRemoteAppWorkspace

## SYNOPSIS
Retrieves information about an Azure RemoteApp workspace.

## SYNTAX

```
Get-AzureRemoteAppWorkspace [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRemoteAppWorkspace** cmdlet retrieves information about an Azure RemoteApp workspace.

## EXAMPLES

### Example 1: Retrieve information about a workspace
```
PS C:\>Get-AzureRemoteAppWorkspace
ClientUrl                               EndUserFeedName
---------                               ---------------
https://www.remoteapp.windowsazure.com/ Contoso Work Applications
```

This command retrieves information about the Azure RemoteApp workspace.

## PARAMETERS

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

[Set-AzureRemoteAppWorkspace](.\Set-AzureRemoteAppWorkspace.md)


