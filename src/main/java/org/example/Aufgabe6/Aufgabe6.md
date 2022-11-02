<b>Aufgabe 6:</b></br>
Lese mit einem Scanner den eingegebenen Input ein  und speichere diesen in einer Variabel ab.
Gebe anschliessend die Variabel aus.

<b>Theorie:</b></br>
Mit einem Scanner kann man Input aus der Konsole einlesen. 

Einen neuen Scanner initialisiert man so:
```
Scanner scanner = new Scanner(System.in);
```

Dies sind verschiedene Optionen den eingelesenen Wert in einer Variabel zu speichern:
```
int input = scanner.nextInt();
String input = scanner.next();
String input = scanner.nextLine();
```

Weitere Links: </br>
<a href="https://www.w3schools.com/java/java_user_input.asp">User Input</a>