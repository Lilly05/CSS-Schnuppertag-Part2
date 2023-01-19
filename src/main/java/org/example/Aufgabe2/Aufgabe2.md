<h1>Aufgabe 2</h1>
Erstelle zwei Variablen mit zwei Zahlen und gebe mit if/ else aus, 
ob die beiden Zahlen gleich gross sind, oder welche Zahl grösser ist

<h1>Theorie:</h1>
Um Bedingungen festzulegen, ob Code ausgeführt werden soll oder nicht, verwendet man if/else. 
Die Bedingung schreibt man zwischen die beiden runden Klammern.

if(Bedingung) {dann ... }</br>
else { ... }

<b>Verschiedene Arten von Bedingungen:</b> </br>
nummer1 == nummer2 <b><- nummer1 und nummer2 sind gleich </b></br>
nummer1 < nummer2 <b><- nummer1 ist kleiner als nummer2</b></br>
nummer1 > nummer2 <b><- nummer1 ist grösser als nummer2</b></br>
nummer1 <= nummer2 <b>nummer1 ist kleiner oder gleich wie nummer2</b></br>
nummer1 >= nummer2 <b>nummer1 ist grösser oder gleich wie nummer2</b></br>
text1.equals(text2) <b><- text1 ist gleich wie text2</b></br>
!text1.equals(text2) <b>text1 ist nicht gleich wie text2</b>


Beispiel:</br>
```
int one = 1; 
int two = 1;

if(one == two){
    System.out.println("Die Zahlen sind gleich");
} else {
    System.out.println("Die Zahlen sind nicht gleich");
}
```

Weitere Links:</br>
<a href="https://www.w3schools.com/java/java_conditions.asp">If else<a>