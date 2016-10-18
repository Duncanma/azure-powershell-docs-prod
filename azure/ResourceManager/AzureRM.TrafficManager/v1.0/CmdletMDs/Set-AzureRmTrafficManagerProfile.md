---
external help file: Microsoft.Azure.Commands.TrafficManager.dll-Help.xml
online version: .\Add-AzureRmTrafficManagerEndpointConfig.md
schema: 2.0.0
updated_at: 10/14/2016 7:06 AM
ms.date: 10/14/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.TrafficManager/v1.0/CmdletMDs/Set-AzureRmTrafficManagerProfile.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/a56d0e01e65c2c33aa2af13dd29addc94ead6e88/azureps-cmdlets-docs/ResourceManager/AzureRM.TrafficManager/v1.0/CmdletMDs/Set-AzureRmTrafficManagerProfile.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Set-AzureRmTrafficManagerProfile

## SYNOPSIS
Updates a Traffic Manager profile.

## SYNTAX

```
Set-AzureRmTrafficManagerProfile -TrafficManagerProfile <TrafficManagerProfile> [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureRmTrafficManagerProfile** cmdlet updates an azure_2 Traffic Manager profile.
This cmdlet updates the settings of the profile from a local profile object.
You can specify the profile object either by using the *TrafficManagerProfile* parameter or by using the pipeline.

You can obtain a local object that represents a profile by using the Get-AzureRmTrafficManagerProfile cmdlet.
Modify the object locally and then use **Set-AzureRmTrafficManagerProfile** to commit your changes.

## EXAMPLES

### Example 1: Update a profile
```
PS C:\>$TrafficManagerProfile = Get-AzureRmTrafficManagerProfile -Name "ContosoProfile" -ResourceGroupName "ResourceGroup11" 
PS C:\> $TrafficManagerProfile.ProfileStatus = Disabled
PS C:\> Set-AzureRmTrafficManagerProfile -TrafficManagerProfile $TrafficManagerProfile
```

The first command gets an azure_2 Traffic Manager profile by using the Get-AzureRmTrafficManagerProfile cmdlet.
The command stores the profile locally in the $TrafficManagerProfile variable.

The second command changes that profile locally.
This command disables the profile.

The third command updates the Traffic Manager profile named ContosoProfile to match the local value in $TrafficManagerProfile.

## PARAMETERS

### -TrafficManagerProfile
Specifies a local **TrafficManagerProfile** object.
This cmdlet updates Traffic Manager to match this local object.

```yaml
Type: TrafficManagerProfile
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Azure.Commands.Network.TrafficManagerProfile
This cmdlet accepts a **TrafficManagerProfile** object.

## OUTPUTS

### Microsoft.Azure.Commands.Network.TrafficManagerProfile
This cmdlet returns a **TrafficManagerProfile** object.

## NOTES

## RELATED LINKS

[Add-AzureRmTrafficManagerEndpointConfig](.\Add-AzureRmTrafficManagerEndpointConfig.md)

[Get-AzureRmTrafficManagerProfile](.\Get-AzureRmTrafficManagerProfile.md)

[New-AzureRmTrafficManagerProfile](.\New-AzureRmTrafficManagerProfile.md)

[Remove-AzureRmTrafficManagerEndpointConfig](.\Remove-AzureRmTrafficManagerEndpointConfig.md)

[Remove-AzureRmTrafficManagerProfile](.\Remove-AzureRmTrafficManagerProfile.md)

