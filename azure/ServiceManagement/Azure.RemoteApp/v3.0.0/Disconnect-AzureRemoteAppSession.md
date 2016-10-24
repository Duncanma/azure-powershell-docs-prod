---
external help file: Microsoft.WindowsAzure.Commands.RemoteApp.dll-Help.xml
online version: a493994e-7e5c-4331-ad55-4c5233580fa2
schema: 2.0.0
ms.assetid: E5E8587A-704C-48CB-9C08-452D5D0CFAEB
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.RemoteApp/v3.0.0/Disconnect-AzureRemoteAppSession.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.RemoteApp/v3.0.0/Disconnect-AzureRemoteAppSession.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Disconnect-AzureRemoteAppSession

## SYNOPSIS
Disconnects an Azure RemoteApp session.

## SYNTAX

```
Disconnect-AzureRemoteAppSession [-CollectionName] <String> [-UserUpn] <String> [-Profile <AzureSMProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Disconnect-AzureRemoteAppSession** cmdlet disconnects a user's Azure RemoteApp session.
The user's client disconnects from their Azure RemoteApp session, but the user's programs continue to run.

## EXAMPLES

### Example 1: Disconnect a user's session
```
PS C:\>Disconnect-AzureRemoteAppSession -CollectionName "ContosoApps" -UserUpn "PattiFuller@contoso.com"
```

This command disconnects the Azure RemoteApp session in the ContosoApps collection for the user whose UPN is PattiFuller@contoso.com.

## PARAMETERS

### -CollectionName
Specifies the name of the Azure RemoteApp collection.

```yaml
Type: String
Parameter Sets: (All)
Aliases: Name

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -UserUpn
Specifies the User Principal Name (UPN) of a user, for example PattiFuller@contoso.com.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: False
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

[Get-AzureRemoteAppSession](.\Get-AzureRemoteAppSession.md)

[Invoke-AzureRemoteAppSessionLogoff](.\Invoke-AzureRemoteAppSessionLogoff.md)

[Send-AzureRemoteAppSessionMessage](.\Send-AzureRemoteAppSessionMessage.md)


