<h1>Aufgabe 4</h1>
Erstelle einen Array mit 4 verschiedenen Zahlen und gebe die Zahlen mit einem For Loop aus.

<h1>Theorie</h1>
Ein Array ist eine Liste mit Elementen. Die Elemente müssen alle vom gleichen Datentyp sein.

<b>Beispiel</b></br>
Im Array numbers sind die vier Zahlen 1, 2, 3 und 4 gespeichert.
Um auf den Inhalt eines Arrays zuzugreifen schreibt man den Namen des Arrays (in diesem Fall numbers)
mit zwei eckigen Klammern [] und zwischen diese eckigen Klammern die Position des Elements, auf das man zugreifen möchte. Zum Beispiel numbers[1].
```
int[] numbers = {1, 2, 3, 4};
```
<b>Wichtig! Arrays starten immer bei der Position 0!</b></br>
Dies bedeutet numbers[0] würde in diesem Fall 1 ausgeben, numbers[1] -> 2 u.s.w

Mit length bekommt man die Länge des Arrays zurück. Wenn man durch die ganze Länge jedes Element ausgibt, gibt man jedes Element des Arrays aus.
Der Wert i ist in diesem Fall der index (Position) des Elements, das ausgegeben werden soll. i wird immer erhöht bis es die gleiche Nummer, wie die Länge des Arrays hat.
```
for(int i = 0; i < arrayName.length; i++){
    System.out.println(arrayName[i]);
}
```

Weitere Links: </br>
<a href="https://www.w3schools.com/java/java_arrays.asp">Arrays</a>
