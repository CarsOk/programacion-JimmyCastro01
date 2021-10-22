# CLASE 13SEPTIEMBRE 

Sacar promedio en los diferentes plataformas


##  CODIGO DE PRUEBA VISUAL BASIC
Sub inicio()

    n1 = Int(InputBox("primera nota"))
    n2 = Int(InputBox("segunda nota"))
    n3 = Int(InputBox("tercera nota"))
    n4 = Int(InputBox("cuarta nota"))
    n5 = Int(InputBox("quinta nota"))
    x = n1 + n2 + n3 + n4 + n5
    y = x / 5
    If (y > 7) Then
        MsgBox " Segun la nota" & n & " el estudiante ganó"
    Else
        MsgBox " segun la nota" & n & " el estudiante perdió"
    End If
End Sub

<img src="img/visual2.jpg" width="1000">

## CODIGO DART

```
void main() {
 int  n = 8;

  if (n > 10){
    print("El promedio del estudiante "n" es mayor que 10 (APROBADO)");
  }else{
    print("El promedio del estudiante "n" es menor o igual que 10 (REPROBADO)");
  }

}

```

## DIAGRAMA DE FLUJO STAR UML


<img src="img/uml3.jpg" width="1000">
