<b>Aufgabe 5:</b></br>
Gebe einen 2D Array, (9 Zahlen über 3 Reihen, also 3 Zahlen per Reihe), per For Schleife aus.

<b>Theorie:</b></br>
Ein 2D Array hat 2 Dimensionen, also man kann Reihen mit Elementen erstellen

```
int[][] numbers = new int[][]{
            {1,2, 3},
            {11,12,13}
    };
```

System.out.println(numbers[0][1]);</br>
Dies würde 2 ausgeben

System.out.println(numbers[1][1]);</br>
Dies würde 12 ausgeben

Dies ist eine verschachtelte For Schleife. Da ein 2d Array zwei Dimensionen hat,
braucht man zwei For Schleifen. 
In der ersten For Schleife looped man, wie beim normalen Array über die Länge.
Im der zweiten For Schleife looped man über die Länge der Reihe. So kommt man an jedes Element.</br>
<b>Zuerst geht man durch jede Reihe und dann durch jedes Element in der Reihe.</b>
```
for(int i = 0; i < arrayName.length; i++){
    for(int j = 0; j < arrayName[i].length; j++){
        System.out.println(arrayName[i][j]);
    }
    System.out.println("\n"); // Dies ist ein Zeilenumbruch
}
```


