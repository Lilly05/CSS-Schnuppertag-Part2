<h1>Aufgabe 6:</h1>
Lese mit einem Scanner den eingegebenen Input ein  und speichere diesen in einer Variabel ab.
Gebe anschliessend die Variabel aus. Du kannst selbst entscheiden, ob du Text oder Zahlen einlesen möchtest. 
Aufpassen! Wenn du dem Scanner angibst, eine Zahl speichern zu wollen, aber dann Text eingibst, gibt es einen Fehler!

<h1>Theorie:</h1>
Mit einem Scanner kann man Input aus der Konsole einlesen. Das heisst man kann auf der Konsole etwas eingeben und anschliessend z.B in einer Variabel speichern.

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
Wenn man so ein Code dann ausführt, geht die Konsole auf und es passiert erst mal nichts. Man muss auf der Konsole etwas eingeben und dann enter klicken. 
So wird die Eingabe dann eingelesen und in der Variabel gespeichert. 

Weitere Links: </br>
<a href="https://www.w3schools.com/java/java_user_input.asp">User Input</a>