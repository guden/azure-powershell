---
external help file: Microsoft.Azure.PowerShell.Cmdlets.Resources.dll-Help.xml
Module Name: Az.Resources
online version: https://docs.microsoft.com/powershell/module/az.resources/get-azmanagementgroup/
schema: 2.0.0
---

# Remove-AzManagementGroupHierarchySetting

## SYNOPSIS
Deletes all Hierarchy Settings under the current tenant

## SYNTAX

### DeleteOperation
```
Remove-AzManagementGroupHierarchySetting  [-GroupName] <String> [-DefaultProfile <IAzureContextContainer>] 
```

## DESCRIPTION
The Remove-AzManagementGroupHierarchySetting cmdlet Removes all hierarchy settings under the current tenant.

## EXAMPLES

### Example 1: Remove Hierarchy Settings
```powershell
Remove-AzManagementGroupHierarchySetting -GroupName c7a87cda-9a66-4920-b0f8-869baa04efe0
```

```output
```

## PARAMETERS

### -GroupName
Management Group Id of the Root Management Group

```yaml
Type: System.String
Parameter Sets: GetOperation
Aliases: GroupId

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### None

## NOTES

## RELATED LINKS

