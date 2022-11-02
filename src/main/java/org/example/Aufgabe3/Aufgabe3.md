<b>Aufgabe 3</b></br>
Teil 1 For Schleifen:</br>
Erstelle eine For Schleife, die in 4er Schritten alle Zahlen bis 100 ausgibt

Teil 2 While Schleifen:</br>
Erstelle eine While Schleife, in jedem Durchlauf eine neue random Zahl bis 100
generiert. Sobald diese random Zahl über 50 ist, soll die Schleife abbrechen. 

<b>Theorie</b></br>
For Schleife: Man weiss bereits, wie viel mal die Schleife durchlaufen muss.</br>
While Schleife: Es ist noch nicht bekannt, wie viel mal die Schleife durchlaufen muss.</br>
<b>Meistens kann man jedoch beide Schleifen benutzen.</b>

Beispiel:</br>
Diese Forschleife zählt bis 20 hoch und wird in jedem Durchgang um 1 erhöht
```
for(int i = 0; i <= 20; i++){
    System.out.println(i);
}
```
int i = 0; <- Variabel mit dem Wert 0 wird initialisiert</br>
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
<b>Wichtig!</b> Man kann eine while Schleife mit break vorzeitig beenden und mit continue direkt zum nächsten Durchlauf springen!

Weitere Links:</br>
<a href="https://www.w3schools.com/java/java_while_loop.asp">While Loop</a></br>
<a href="https://www.w3schools.com/java/java_for_loop.asp">For Loop</a></br>
<a href="https://www.w3schools.com/java/java_math.asp">Random Zahl generieren</a>