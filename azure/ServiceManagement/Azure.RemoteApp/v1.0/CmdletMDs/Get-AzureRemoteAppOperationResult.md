---
external help file: Microsoft.WindowsAzure.Commands.RemoteApp.dll-Help.xml
online version: .\Disconnect-AzureRemoteAppSession.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.RemoteApp/v1.0/CmdletMDs/Get-AzureRemoteAppOperationResult.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ServiceManagement/Azure.RemoteApp/v1.0/CmdletMDs/Get-AzureRemoteAppOperationResult.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRemoteAppOperationResult

## SYNOPSIS
Retrieves the result of an azure_2 RemoteApp operation.

## SYNTAX

```
Get-AzureRemoteAppOperationResult [-TrackingId] <String> [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRemoteAppOperationResult** cmdlet retrieves the result of a long-running azure_2 RemoteApp operation.
azure_2 RemoteApp uses long-running operations for many actions that require processing by the service and cannot return immediately.
Examples of cmdlets that return tracking IDs include **Update-AzureRemoteAppCollection**, **Set-AzureRemoteAppWorkspace**, **Disconnect-AzureRemoteAppSession**, and others.

## EXAMPLES

### Example 1: Use a tracking ID to get an operation result
```
PS C:\>$result = New-AzureRemoteAppCollection -CollectionName Contoso -ImageName "Windows Server 2012 R2" -Plan Standard -Location "West US" -Description CloudOnly
PS C:\> Get-AzureRemoteAppOperationResult -TrackingId $result.Tracking
```

This command saves the tracking ID returned from an azure_2 RemoteApp operation.
The tracking ID is passed to **Get-AzureRemoteAppOperationResult** in the command that follows.

## PARAMETERS

### -TrackingId
Specifies the tracking ID of an operation.

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
ps_azureprofile_description

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

[Disconnect-AzureRemoteAppSession](.\Disconnect-AzureRemoteAppSession.md)

[Set-AzureRemoteAppWorkspace](.\Set-AzureRemoteAppWorkspace.md)

[Update-AzureRemoteAppCollection](.\Update-AzureRemoteAppCollection.md)

