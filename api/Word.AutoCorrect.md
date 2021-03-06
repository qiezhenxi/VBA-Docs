---
title: AutoCorrect Object (Word)
keywords: vbawd10.chm2377
f1_keywords:
- vbawd10.chm2377
ms.prod: word
api_name:
- Word.AutoCorrect
ms.assetid: dea9b72c-4378-05ac-ec4b-51cf3af3f2a3
ms.date: 06/08/2017
---


# AutoCorrect Object (Word)

Represents the AutoCorrect functionality in Word.


## Remarks

Use the  **[AutoCorrect](Word.Application.AutoCorrect.md)** property to return the **AutoCorrect** object. The following example enables the AutoCorrect options and creates an AutoCorrect entry.


```vb
With AutoCorrect 
 .CorrectCapsLock = True 
 .CorrectDays = True 
 .Entries.Add Name:="usualy", Value:="usually" 
End With
```

The  **[Entries](Word.AutoCorrect.Entries.md)** property returns the **[Entries](Word.AutoCorrect.Entries.md)** object that represents the AutoCorrect entries in the **AutoCorrect** dialog box.


## See also


[Word Object Model Reference](./overview/Word/object-model.md)


