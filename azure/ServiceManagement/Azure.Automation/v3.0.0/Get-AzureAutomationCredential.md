---
external help file: Microsoft.Azure.Commands.Automation.dll-Help.xml
online version: 4034893b-0f12-4640-92b6-7a6ee003413d
schema: 2.0.0
ms.assetid: 76B510FE-A17A-40CD-9AF0-89E433598757
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Automation/v3.0.0/Get-AzureAutomationCredential.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ServiceManagement/Azure.Automation/v3.0.0/Get-AzureAutomationCredential.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureAutomationCredential

## SYNOPSIS
Gets an Azure Automation credential.

## SYNTAX

### ByAll (Default)
```
Get-AzureAutomationCredential [-AutomationAccountName] <String> [-Profile <AzureSMProfile>]
 [<CommonParameters>]
```

### ByName
```
Get-AzureAutomationCredential [-Name] <String> [-AutomationAccountName] <String> [-Profile <AzureSMProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureAutomationCredential** cmdlet gets one or more Microsoft Azure Automation credentials.
By default, all credentials are returned.
To get a specific credential, specify its name.

## EXAMPLES

### Example 1: Get all credentials
```
PS C:\> Get-AzureAutomationCredential -AutomationAccountName "Contoso17"
```

This command gets all credentials in the Automation account named Contoso17.

### Example 2: Get a credential
```
PS C:\> Get-AzureAutomationCredential -AutomationAccountName "Contoso17" -Name "MyCredential"
```

This command gets the credential named MyCredential.

## PARAMETERS

### -AutomationAccountName
Specifies the name of the automation account with the credential to retrieve.

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

### -Name
Specifies the name of a credential to retrieve.

```yaml
Type: String
Parameter Sets: ByName
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
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

### Microsoft.Azure.Commands.Automation.Model.CredentialInfo

## NOTES

## RELATED LINKS

[New-AzureAutomationCredential](.\New-AzureAutomationCredential.md)

[Remove-AzureAutomationCredential](.\Remove-AzureAutomationCredential.md)

[Set-AzureAutomationCredential](.\Set-AzureAutomationCredential.md)


