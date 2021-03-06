---
title: TimelineState.Application Property (Excel)
keywords: vbaxl10.chm949073
f1_keywords:
- vbaxl10.chm949073
ms.prod: excel
ms.assetid: 5b919557-9aeb-acc7-f717-8457f57e44fb
ms.date: 06/08/2017
---


# TimelineState.Application Property (Excel)

Returns an  **[Application](application-object-excel.md)** object that represents the Microsoft Excel application. Read-only.


## Syntax

 _expression_ . **Application**

 _expression_ A variable that represents a[TimelineState Object (Excel)](timelinestate-object-excel.md) object.


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


#### Other resources



[TimelineState Object](timelinestate-object-excel.md)

