## CODIGO DE PRUEBA CELLS VISUAL BASIC

```
Sub inicio()
    recibe.Cells(2, 1) = formul.Cells(2, 3)
    recibe.Cells(2, 3) = formul.Cells(4, 3)
        MsgBox "COMPLETADO"
    formul.Cells(2, 3) = ""
    formul.Cells(4, 3) = ""
    
End Sub
```


## CODIGO DE PRUEBA FUNCTION VISUAL BASIC

```

Function misnotas(n1, n2, n3, n4, n5)
    promedio = (n1 + n2 + n3 + n4 + n5) / 5
    If (promedio > 7) Then
        misnotas = " CON ESTE PROMEDIO  " & promedio & " APROBO"
    Else
        misnotas = " CON ESTE PROMEDIO  " & promedio & " REPROBO"
    End If

End Function


```
