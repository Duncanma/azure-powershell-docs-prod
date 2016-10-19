---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: .\Get-AzureRouteTable.md
schema: 2.0.0
ms.assetid: 5673803B-4005-4588-9E22-47B3729C208D
updated_at: 10/19/2016 10:11 PM
ms.date: 10/19/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v0.9.8/New-AzureRouteTable.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/4b5e5bf2b9726cfa193914d0aa3066271dbb9e41/azureps-cmdlets-docs/ServiceManagement/Azure.Networking/v0.9.8/New-AzureRouteTable.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# New-AzureRouteTable

## SYNOPSIS
Creates a route table.

## SYNTAX

```
New-AzureRouteTable [-Name] <String> [-Location] <String> [[-Label] <String>] [-Profile <AzureProfile>]
 [-PipelineVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureRouteTable** cmdlet creates a route table in a specified location.
You can add user-defined routes to the route table.
You can associate the route table to a subnet in a virtual network.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Label
Specifies a description for the new route table.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Location
Specifies the location in which this cmdlet creates the route table.
To obtain valid locations, use the **Get-AzureLocation** cmdlet.

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

### -Name
Specifies a name for the route table that this cmdlet creates.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PipelineVariable
Not Specified```yaml
Type: String
Parameter Sets: (All)
Aliases: pv

Required: False
Position: Named
Default value: None
Accept pipeline input: False
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

[Get-AzureRouteTable](.\Get-AzureRouteTable.md)

[Remove-AzureRouteTable](.\Remove-AzureRouteTable.md)


