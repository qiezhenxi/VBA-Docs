---
title: ModelTables.Application Property (Excel)
keywords: vbaxl10.chm935073
f1_keywords:
- vbaxl10.chm935073
ms.prod: excel
ms.assetid: 8d44b48b-47ed-02db-161f-449a166be50e
ms.date: 06/08/2017
---


# ModelTables.Application Property (Excel)

Returns an  **[Application](Excel.Application(object).md)** object that represents the Microsoft Excel application. Read-only.


## Syntax

 _expression_. `Application`

 _expression_ A variable that represents a [ModelTables Object (Excel)](Excel.modeltables.md) object.


## Example

This example displays a message about the application that created  `myObject`.


```vb
Set myObject = ActiveWorkbook 
If myObject.Application.Value = "Microsoft Excel" Then 
 MsgBox "This is an Excel Application object." 
Else 
 MsgBox "This is not an Excel Application object." 
End If
```


## Property value

 **APPLICATION**


## See also



[ModelTables Object](Excel.modeltables.md)

