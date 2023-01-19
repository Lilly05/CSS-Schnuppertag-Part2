<h1>Aufgabe 5:</h1>
Gebe einen 2D Array, (9 Zahlen über 3 Reihen, also 3 Zahlen per Reihe), per For Schleife aus.

<h1>Theorie:</h1>
Ein 2D Array hat 2 Dimensionen, also man kann Reihen mit Elementen erstellen

```
int[][] numbers = new int[][]{
            {1,2, 3},
            {11,12,13}
    };
```
Um auf ein Element dieses 2D Arrays zuzugreifen, braucht man wie bei einem normalen Array den Namen des 2D Arrays,
sowie eckige Klammern. Aber nicht wie beim normalen Array nur ein Paar eckige Klammern, sondern zwei. Wieder beginnt der Index bei 0 und nicht bei 1. 
Dies bedeutet, sodass man die 1 aus dem numbers Array bekommt, muss man numbers[0][0] ausgeben.

System.out.println(numbers[0][1]);</br>
Dies würde 2 ausgeben

System.out.println(numbers[1][1]);</br>
Dies würde 12 ausgeben

Dies ist eine verschachtelte For Schleife. Da ein 2d Array zwei Dimensionen hat,
braucht man zwei For Schleifen. 
In der ersten For Schleife looped man, wie beim normalen Array über die Länge.
Im der zweiten For Schleife looped man über die Länge der Reihe. So kommt man an jedes Element. Um über die Länge einer Reihe zu loopen
muss man die Reihe per Index angeben z.B numbers[1] und dann .length anhängen. Also numbers[1].length. Dies würde nun 11, 12 und 13 ausgeben.</br>
<b>Zuerst geht man durch jede Reihe und dann durch jedes Element in der Reihe.</b>
```
for(int i = 0; i < arrayName.length; i++){
    for(int j = 0; j < arrayName[i].length; j++){
        System.out.println(arrayName[i][j]);
    }
    System.out.println("\n"); // Dies ist ein Zeilenumbruch
}
```

Weitere Links: </br>
<a href="https://www.w3schools.com/java/java_arrays_multi.asp">2D Arrays</a>


