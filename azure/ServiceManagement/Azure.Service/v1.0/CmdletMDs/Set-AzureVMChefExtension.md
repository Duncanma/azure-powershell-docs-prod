---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: .\Get-AzureVMChefExtension.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v1.0/CmdletMDs/Set-AzureVMChefExtension.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ServiceManagement/Azure.Service/v1.0/CmdletMDs/Set-AzureVMChefExtension.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, content
manager: visual-studio-china
---

# Set-AzureVMChefExtension

## SYNOPSIS
Adds the Chef extension to the virtual machine.

## SYNTAX

### Windows (Default)
```
Set-AzureVMChefExtension [-Version <String>] -ValidationPem <String> [-ClientRb <String>]
 [-BootstrapOptions <String>] [-RunList <String>] [-ChefServerUrl <String>] [-ValidationClientName <String>]
 [-OrganizationName <String>] [-BootstrapVersion <String>] [-Windows] -VM <IPersistentVM>
 [-Profile <AzureSMProfile>] [-InformationAction <ActionPreference>] [-InformationVariable <String>]
 [<CommonParameters>]
```

### Linux
```
Set-AzureVMChefExtension [-Version <String>] -ValidationPem <String> [-ClientRb <String>]
 [-BootstrapOptions <String>] [-RunList <String>] [-ChefServerUrl <String>] [-ValidationClientName <String>]
 [-OrganizationName <String>] [-BootstrapVersion <String>] [-Linux] -VM <IPersistentVM>
 [-Profile <AzureSMProfile>] [-InformationAction <ActionPreference>] [-InformationVariable <String>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureVMChefExtension** cmdlet adds the Chef extension to the virtual machine.

## EXAMPLES

### Example 1: Add a Chef extension to a Windows virtual machine
```
PS C:\>Set-AzureVMChefExtension -VM $VM -ValidationPem "C:\\myorg-validator.pem" -ClientRb "C:\\client.rb" -RunList "Apache" -Windows;
```

This command adds a Chef extension to a Windows virtual machine.
When the virtual machine comes up, it is bootstrapped with Chef and runs Apache on it.

### Example 2: Add a Chef extension to a Windows virtual machine with bootstrapping
```
PS C:\>Set-AzureVMChefExtension -VM $VM -ValidationPem "C:\\myorg-validator.pem" -BootstrapOptions '{"chef_node_name":"your_node_name","chef_server_url":"https://api.opscode.com/organizations/some-org", "validation_client_name":"some-org-validator"}' -RunList "Apache" -Windows;
```

This command adds the Chef extension to a Windows virtual machine.
When the virtual machine launches, it is bootstrapped with Chef and runs Apache on it.
After bootstrapping, the virtual machine refers to the *BootstrapOptions* specified in JSON format.

### Example 3: Add a Chef extension to a Windows virtual machine and install Apache and GIT
```
PS C:\>Set-AzureVMChefExtension -VM $VM -ValidationPem "C:\\myorg-validator.pem" -ChefServerUrl "http://ipaddress:port" -ValidationClientName "MyOrg-Validator" -RunList "apache, git" -Windows;
```

This command adds the Chef extension to a Windows virtual machine.
When the virtual machine launches, it is bootstrapped with Chef and have Apache and GIT installed.
If you do not provide the client.rb, you need to provide the Chef server URL and validation client name.

### Example 4: Add a Chef extension to a Linux virtual machine
```
PS C:\>Set-AzureVMChefExtension -VM $VM -ValidationPem "C:\\myorg-validator.pem" -ChefServerUrl "http://ipaddress:port" -OrganizationName "MyOrg" -Linux;
```

This command adds the Chef extension to a Linux virtual machine.
When the virtual machine launches, it is bootstrapped with Chef.
If you do not provide the client.rb, you need to provide the Chef server URL and organization.

## PARAMETERS

### -Version
Specifies the version number of the Chef extension.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ValidationPem
Specifies the Chef validator .pem file path

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ClientRb
Specifies the full path of the Chef client.rb.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -BootstrapOptions
```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -RunList
Specifies the Chef node run list.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ChefServerUrl
```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ValidationClientName
@{Text=}

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -OrganizationName
Specifies the organization name of the Chef extension.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -BootstrapVersion
Specifies the version of chef-client to be installed with the extension.```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Windows
Indicates that this cmdlet creates a Windows virtual machine.

```yaml
Type: SwitchParameter
Parameter Sets: Windows
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

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

### -InformationAction
@{Text=}```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
@{Text=}```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Linux
Indicates that this cmdlet creates a Linux based virtual machine.

```yaml
Type: SwitchParameter
Parameter Sets: Linux
Aliases: 

Required: True
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

[Get-AzureVMChefExtension](.\Get-AzureVMChefExtension.md)

[Remove-AzureVMChefExtension](.\Remove-AzureVMChefExtension.md)

[Azure Service Cmdlets](.\Azure.Service.md)
