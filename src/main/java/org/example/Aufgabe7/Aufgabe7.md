<h1>Aufgabe 7</h1>
Erstelle eine Methode, die eine zufällige Zahl zurückgibt, und gebe diese
auf der Konsole aus.

<h1>Theorie</h1>
Mit Methoden kann man seinen Code viel schöner und übersichtlicher programmieren.
Der Vorteil ist ebenfalls, dass man Code, den man mehrmals gebraucht, nicht kopieren muss, 
sondern einfach die Methode aufrufen muss.

Die Main Methode hast du in jedem Java File gsehen, in denen du diese Übungen löst
```
public static void main(String[] args) {

}
```

Nun kannst du deine eigenen Methoden erstellen. Wichtig ist, dass du die Funktionen AUSSERHALB
der Main Methode programmierst. 

Methoden können Rückgabewerte haben, müssen aber nicht. 
Wenn du eine Methode erstellen willst, die einen String zurückgibt, sieht das folgendermassen aus:
```
public static String returnQuote(){
    String text = "Hallo Leben";
    return text;
}
```
Mit dem Schlüsselwort return gibt man einen Wert zurück

Eine Methode, die nichts zurückgibt, sieht so aus:
```
public static void textAusgeben(){
    System.out.println("Hello!!");
}
```

In den Klammern nach dem Namen der Methode, kann man Parameter mitgeben.
Das sind Werte, die in der Funktion gebraucht werden. Man gibt aber nur eine KOPIE der Werte mit.
Das heisst, die originalen Werte werden nicht verändert, wenn man sie in der Methode bearbeitet.

Beispiel Methode mit Parameter:

```
public static int multipliziereMitVier(int number){
    int newNumber = number * 4;
    return newNumber;

}
```
Hier wird der Wert, der als Parameter mitgegeben wird, mit 4 multipliziert.

Es ist wichtig, Funktionen gut zu benennen, sodass direkt klar ist, was die Funktion genau macht.

Die Methoden, die wir selbst geschrieben haben, können wir innerhalb der Main Methode oder innerhalb einer anderen Methode aufrufen, aber nicht direkt in der Methode selbst.

Gehen wir davon aus, unser Programm sieht so aus:

```
public class Main {
    public static void main(String[] args) {
        int newNumber = multipliziereMitVier(4);
        textAusgeben();
        String quote = returnQuote();
    }
    
    public static String multipliziereMitVier(int number){
        int newNumber = number * 4;
        return newNumber;
    }
    
    public static void textAusgeben(){
        System.out.println("Hello!!);
    }
    
    public static String returnQuote(){
        String text = "Hallo Leben";
        return text;
    }
}

```
`multipliziereMitVier` verlangt einen Parameter, wir geben 4 mit und erhalten 16, da 4 * 4.

`textAusgeben` verlangt keine Parameter und gibt nur Text auf der Konsole aus und gibt keinen Wert zurück

`returnQuote` verlangt keine Parameter und gibt "Hallo Leben" zurück.

Weitere Links:</br>
<a href="https://www.w3schools.com/java/java_methods.asp">Methoden</a></br>
<a href="https://www.w3schools.com/java/java_methods_param.asp">Methoden mit Parametern</a></br>
<a href="https://www.w3schools.com/java/java_math.asp">Random Zahl generieren</a>
