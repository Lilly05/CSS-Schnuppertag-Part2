<h1>Aufgabe 3</h1>

<strong>Teil 1 -</strong> for-Schleifen:</br>
Erstelle eine for-Schleife, die in 4er-Schritten alle Zahlen bis 100 ausgibt.

<strong>Teil 2 - </strong> while-Schleifen:</br>
Erstelle eine while-Schleife, die in jedem Durchlauf eine neue zufällige Zahl bis 100
generiert. Sobald diese Zahl über 50 ist, soll die Schleife abbrechen. 

<h1>Theorie</h1>
<b>Wann benutzt man welche Schleife?</b></br>
for-Schleife: Man weiss bereits, wie viel mal die Schleife durchlaufen muss.</br>
while-Schleife: Es ist noch nicht bekannt, wie viel mal die Schleife durchlaufen muss.</br>
<b>Meistens kann man jedoch beide Schleifen benutzen.</b>

Beispiel:</br>
Diese Forschleife zählt bis 20 hoch und wird in jedem Durchgang um 1 erhöht
```
for(int i = 0; i <= 20; i++){
    System.out.println(i);
}
```
int i = 0; <- Variable mit dem Wert 0 wird initialisiert und deklariert</br>
i <= 20 <- Bedingung, wie lange die Forschleife durchlaufen soll</br>
i++ <- i wird um 1 erhöht

```
int number = 0;
while(number < 10){
    System.out.println("number before:" + number);
    int randomNumber = (int)(Math.random() * 11); // random Zahl bis 10
    number += randomNumber;
    System.out.println("number after:" + number);
}
```
<b>Wichtig!</b> Man kann eine while Schleife mit break; vorzeitig beenden und mit continue; direkt zum nächsten Durchlauf springen!

Weitere Links:</br>
<a href="https://www.w3schools.com/java/java_while_loop.asp">While Loop</a></br>
<a href="https://www.w3schools.com/java/java_for_loop.asp">For Loop</a></br>
<a href="https://www.w3schools.com/java/java_math.asp">Random Zahl generieren</a>