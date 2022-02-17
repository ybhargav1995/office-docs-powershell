---
external help file: Microsoft.Exchange.TransportMailflow-Help.xml
online version: https://docs.microsoft.com/powershell/module/exchange/get-atpbuiltinprotectionrule
applicable: Exchange Online, Exchange Online Protection
title: Get-ATPBuiltInProtectionRule
schema: 2.0.0
author: chrisda
ms.author: chrisda
ms.reviewer:
---

# Get-ATPBuiltInProtectionRule

## SYNOPSIS
This cmdlet is available only in the cloud-based service.

Use the Get-ATPBuiltInProtectionRule cmdlet to view the Built-in protection profile that effectively provides default policies for Safe Links and Safe Attachments in Microsoft Defender for Office 365.

**Note**: We recommend that you use the Exchange Online PowerShell V2 module to connect to Exchange Online PowerShell. For instructions, see [Connect to Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell).

For information about the parameter sets in the Syntax section below, see [Exchange cmdlet syntax](https://docs.microsoft.com/powershell/exchange/exchange-cmdlet-syntax).

## SYNTAX

```
Get-ATPBuiltInProtectionRule [[-Identity] <DehydrateableRuleIdParameter>] [-State <RuleState>] [<CommonParameters>]
```

## DESCRIPTION
You need to be assigned permissions before you can run this cmdlet. Although this topic lists all parameters for the cmdlet, you may not have access to some parameters if they're not included in the permissions assigned to you. To find the permissions required to run any cmdlet or parameter in your organization, see [Find the permissions required to run any Exchange cmdlet](https://docs.microsoft.com/powershell/exchange/find-exchange-cmdlet-permissions).

## EXAMPLES

### Example 1
```powershell
Get-ATPBuiltInProtectionRule
```

This example shows the Built-in protection profile in the organization.

## PARAMETERS

### -Identity
The Identity parameter specifies the Built-in protection profile that you want to view. You can use any value that uniquely identifies the profile. For example:

- Name
- Distinguished name (DN)
- GUID

By default, every organization has one Built-in protection profile named ATP Built-In Protection Rule.

```yaml
Type: DehydrateableRuleIdParameter
Parameter Sets: (All)
Aliases:
Applicable: Exchange Online, Exchange Online Protection

Required: False
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -State
The State parameter filters the results by the state of the Built-in protection profile. Valid values are:

- Disabled
- Enabled

```yaml
Type: RuleState
Parameter Sets: (All)
Aliases:
Accepted values: Enabled, Disabled
Applicable: Exchange Online, Exchange Online Protection

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/p/?LinkID=113216).

## INPUTS

###  

## OUTPUTS

###  

## NOTES

## RELATED LINKS
