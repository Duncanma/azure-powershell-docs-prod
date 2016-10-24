---
external help file: Microsoft.Azure.Commands.Compute.dll-Help.xml
online version: 4f9bfbf3-ccdf-4325-96c4-199376cb5d27
schema: 2.0.0
ms.assetid: 07CD1B50-9F76-4E85-B442-3709E8D3E52F
updated_at: 10/24/2016 11:18 PM
ms.date: 10/24/2016
content_git_url: https://github.com/Azure/azure-docs-powershell/blob/master/azureps-cmdlets-docs/ResourceManager/AzureRM.Compute/v2.2.0/Get-AzureRmVMImagePublisher.md
gitcommit: https://github.com/Azure/azure-docs-powershell/blob/7db57df6b5e709a7c001e6de362a1240d7583ae8/azureps-cmdlets-docs/ResourceManager/AzureRM.Compute/v2.2.0/Get-AzureRmVMImagePublisher.md
ms.topic: reference
ms.prod: powershell
ms.service: Azure PowerShell
ms.technology: Azure PowerShell
author: visual-studio-china
keywords: powershell, cmdlet
manager: visual-studio-china
---

# Get-AzureRmVMImagePublisher

## SYNOPSIS
Gets the VMImage publishers.

## SYNTAX

```
Get-AzureRmVMImagePublisher -Location <String> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmVMImagePublisher** cmdlet gets the VMImage publishers.

## EXAMPLES

### Example 1: Get VMImage publishers for a region
```
PS C:\>Get-AzureRmVMImagePublisher -Location "Central US"
```

This command gets the publishers of VMImage instances for the Central US region within your Azure profile.

## PARAMETERS

### -Location
Specifies the location of the VMImage.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureRmVMImage](.\Get-AzureRmVMImage.md)

[Get-AzureRmVMImageOffer](.\Get-AzureRmVMImageOffer.md)

[Get-AzureRmVMImageSku](.\Get-AzureRmVMImageSku.md)

[Save-AzureRmVMImage](.\Save-AzureRmVMImage.md)


