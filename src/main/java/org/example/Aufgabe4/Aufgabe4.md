<b>Aufgabe 4</b></br>
Erstelle einen Array mit 4 verschiedenen Zahlen und gebe die Zahlen mit einem For Loop aus.

<b>Theorie</b></br>
Ein Array ist eine Liste mit Elementen. Die Elemente müssen alle vom gleichen Datentyp sein.

<b>Beispiel</b></br>
Im Array numbers sind die vier Zahlen 1, 2, 3 und 4 gespeichert.
```
int[] numbers = {1, 2, 3, 4};
```
<b>Wichtig! Arrays starten immer bei der Position 0!</b></br>
Dies bedeutet numbers[0] würde in diesem Fall 1 ausgeben, numbers[1] -> 2 u.s.w

Mit length bekommt man die Länge des Arrays zurück, so kann man jedes Element eines Arrays ausgeben.
Der Wert i ist in diesem Fall der index des Elements, das ausgegeben werden soll.
```
for(int i = 0; i < arrayName.length; i++){
    System.out.println(arrayName[i]);
}
```

Weitere Links: </br>
<a href="https://www.w3schools.com/java/java_arrays.asp">Arrays</a>
