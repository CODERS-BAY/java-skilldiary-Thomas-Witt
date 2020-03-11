# 11.03.

Heute haben wir wieder mit Objektorientierter Programmierung gearbeitet (also das, was ich am Montag versäumt habe). Wir haben ein Beispiel eines Fuhrparks gebastelt, dass auch sehr gut zu verstehen war. Danach haben wir an der Aufgabe von Pia über die Personenverwaltung weitergemacht. Es ist bei weitem noch nicht alles klar, aber es geht schon um Welten besser als am Montag. Und die Nachrichten über den Corona-Vierus machen anscheinend auch vor der Codersbay nicht halt. 

# 09.03

Hirn.exe hat einen Fehler verursacht und musste geschlossen werden!

# 06.03.

Das aufsplitten eines Codes in Methoden wird mit dem Tastenkürzel strg+alt+m sehr einfach. Außerdem habe ich heute wieder versucht meinen Kollegen ein wenig weiter zu helfen, und habe wiedereinmal festgestellt, dass ich das Nachhilfe geben sehr mag. Zum einen freue ich mich, wenn ich anderen helfen kann. Und zum anderen ist es eine tolle Überprüfung für mich selber. Wenn ich etwas erklären kann habe ich es wirklich verstanden. Und wenn ich auf eine Frage keine Antwort weiß, weiß ich wo ich weitermachen muss. 

# 02.03.

Heute habe ich den devide-and-conquer fertig gemacht. Das viele Durchdenken letztes mal und das Reflektieren zu Hause hat sich ausgezahlt, denn ich hatte heute das Gefühl, dass ich die Methoden schon wesentlich besser verstanden habe. 
Dann haben wir heute gemeinsam mein "game of life" aufgesplittet und in Methoden unterteilt. Dadurch hat sich zwar die Anzahl an Zeilen in IntelliJ erhöht, aber es ist wesentlich besser lesbar geworden. Und man könnte auf die Methoden öfter zugreifen (was wir in einem Fall sogar gemacht haben: beim "kopieren" von dem prmary auf secondary array).
Zum Schluss habe ich noch den Merge-Sort gemacht. Es hat zwischendurch etwas gehapert, aber ich bin nie wirklich stecken geblieben. Pia hat mir einige Male wirklich gut weiter geholfen, und ich habe es wieder Punktgenau zum Schluss fertig bekommen und gepusht.



# Sechster Tag 
(23.02.2020) <br>
Heute habe ich mich eingehend mit den Methoden auseinandergesetzt. Nach überlegen, mit Kollegen diskutieren und Youtube-Erklärungsvideos schaun bin ich im Verständnis doch etwas weiter gekommen. Was ich noch nicht wirklich intuitiv verstehe ist, wenn einen Methode sich selber aufruft und z.B.: ein Array in einen linken und einen rechten Teil splittet, und dann das selbe für den linken Teil noch einmal macht, wie kann es das geben, dass da nicht die selbe Variable für verschiedene Werte verwendet wird und dadurch Daten verloren gehen. Und selbst wenn das geht (dass es geht weiß ich, das hab ich in Beispielen und youtube gesehen), "wann" kommt dann der rechte Teil dran? In einem "normalen" code kann man verstehen, wie der Computer einfach Zeile für Zeile durchgehen und die Logik folgt einer Reihenfolge. Bei Schleifen werden einige Zeilen einfach, sobald die Schleife erreicht wird, eine bestimmte Anzahl wiederholt und dann geht es im code nach der Schleife weiter. <br>
Aber Methoden machen mir da einen Knopf in meine Logik. Vielleich muss ich mal ein funktionierendes Programm deBugen und Zeile für Zeile mitschaun (und vl sogar mit schreiben) um wirklich zu Verständnis zu kommen. - Ein un-intuitiver Zugang: Etwas, was man nicht verstanden hat, zu schreiben, das dann funktioniert, und dann mit der Lupe zu untersuchen warum es funktioniert. 



# Fünfter Tag

Heute haben wir Vormittag den ersten Test geschrieben. Ich bin ca eine Stund vor Abgabezeitpunkt (der um 12:00 Uhr war) fertig geworden. Ich habe das Gefühl, dass man bei Java mit Verständniss sehr weit kommt. Die genaue Syntax kann man sich schon wo zusammenklauben. Ich hoffe, dass das mit der Zeit einfacher wird. Vielleicht mache ich mir ein Template-Dokument, wo ich sachen wie Scanner und so abspeicher, damit ich immer schnell darauf zugriff habe. 
Am Nachmittag habe ich die Zahlenspirale gemacht. Ich habe zuerst auf einem Blatt Papier, die generelle Logik erarbeitet. Das hat die meiste Zeit in Anspruch genommen. Das übertragen in IntelliJ war wieder (bis auf die obligatorischen Tippfehler) einfach und zügig. 
Gegen Schluss haben wir noch Methoden durchgenommen. Das war anfangs sehr verwirrend. Nachdem ungefähr klar war, wie die Methoden funktionieren, war noch die Syntax herrausfordernd. 
Aber in den allerletzten Minuten bin ich noch fertig geworden mit der Fibonacci-Abfrage.



# Dritter Tag

Diary im Jahre 2020, im Monat 02, am Tag 17. Wenn ich zukünftig alle meine Diarys so benenne (und davorschreibe für welches Fach ich gerade schreibe), kann ich hoffentlich leichter den Überblick behalten. 

Heute habe ich die <h2>"Berechnung des Maximums"</h2> ferig gemacht. 
Im Grund is es nicht schwierig. Das einlesen der Usereingabe in einen Array braucht mehr Zeilen Code als die Berechnung selber. 

Dann gings an den <h2>"Insertion sort"</h2>
ich habe _einen_ Sortieralgorythmus geschrieben. Ob es jetzt wirklich ein insertion sort ist oder nicht, habe ich bis jetzt nicht ganz verstandenl. Naja, es sortiert. Why fix something if it isn't broken?

Anschließend habe ich den <h2>"Leetspeak"</h2> geschrieben. 
Ich muss mir wieder mehr in den Sinn rufen, dass es neben if-Verzweigungen auch switch gibt, und dass es neben for-Schleifen auch while gibt. Und wieder war das einlesen des Userinputs was vom schwierigsten:
```java
String userInput;
        Scanner scanner = new Scanner(System.in);
        userInput = scanner.nextLine();
        char[] singleLetter = userInput.toCharArray();

```
Wichtig ist das next!LINE!, weil der Scanner sonst bei dem Nächsten Leerzeichen abbricht. Und das String-in-Array und umgekehrt hab ich auch noch nicht wirklich im Blut. 
```java
System.out.println(Arrays.toString(singleLetter));
//oder
 String leet = new String(singleLetter);
        System.out.println(leet);
```
Zwischendurch habe ich noch den <h2>CäsarChiffre</h2> korrigiert. Ich habe das Feedback bekommen, dass die Buchsteben, wenn sie über da Z hinaus gehen zu kryptischen Symbolen werden. Ich konnte mich aber erinnern, dass ich das Problem schon behoben hatte. Ich habe mein Cäsar-Chiffre geöffnet und ausgeführt und tatsächlich: kryptische Symbole.
Dann habe ich in meinem Code nachgeschaut, und die 2 If-Verzweigungen die das Problem beheben sollen :
```java
 if (characterJump < 0) {
            characterJump = (characterJump % 26) + 26;
        } else {
            characterJump = characterJump % 26;
        }
```
und
```java
if (i < (26 - characterJump)) {
                changedLetter[i] = (char) (singleLetter[i] + characterJump);
            } else {
                changedLetter[i] = (char) (singleLetter[i] - 26 + characterJump);
            }
```
auch sofort gefunden. Nach einem weiteren Ausführen trat das Problem auch nicht mehr auf. Da hats wohl was mit den verschidenen Versionen, welche gepusht wurde, welche ausgeführt wurde und welche gespeichert wurde zu tun. Sei's wies sei, es geht jetzt auf jeden Fall. 

Abschließend habe ich noch den <h2>Bubble-sort</h2> in angriff genommen. Da wir ih gemeinsam schon durchgegangen haben, habe ich mir nur mehr kurz Gedanken machem müssen, wie genau ich das schreiben will. Ich habe auf einem Block Notizen gemacht und sie dann 1:1 ins IntelliJ übertragen, und es hat gleich geklappt. Ich weis nicht, wie viel davon Geschick und wie viel Glück war. Es geht auf jeden Fall.



# Zweiter Tag Java. 

Heute habe ich mich als Erstes mit dem 
#### Cäsar-Chiffre
 beschäftigt. Ich habe die Eingabe des Chiffre-Werts Idiotensicher gemacht:
```java Scanner scanner = new Scanner(System.in);
        characterJump = scanner.nextInt();
        if (characterJump < 0) {
            characterJump = (characterJump % 26) + 26;
        } else {
            characterJump = characterJump % 26;
```
Dann habe ich die Usereingabe in einen Char-Array umgewandelt:
```java 
        userInput = scanner2.next();
        char[] singleLetter = userInput.toCharArray();
```
und dann jeden Arrayplatz um einen vom User eingegebenen Wert erhöht
(also aus "a" + 3 wird "d")
```java
changedLetter[i] = (char) (singleLetter[i] + characterJump);
```
Und dann die chiffrierte Nachricht ausgegeben. 

Danach ging es weiter mir

#### Arbeit oder Freizeit

Nachdem ich mich mit Videos über Zeit- Datumsformate abgequält habe, hab ich 
erfahren, dass diese Aufgabe einfach mit normalen int-Eingaben zu lösen ist.
Das hat die Sache sehr vereinfacht, und ich habe mir einen Spass draus gemacht, 
die Usereingabe idiotensicher zu machen:
```java
System.out.println("Wie spät ist es? Bitte gib erst die Stunden und dann die Minuten an:");
        do {
            Scanner scanner = new Scanner(System.in);
            hour = scanner.nextInt();
            if (hour < 0) {
                System.out.println("Wenn du negative Zeit entdeckt hast, gehe nach Stockholm und hole dir" +
                        "deinen Nobelpreis ab. Bei der Überprüfung ob Arbeitszeit ist, ist sie aber unangebracht!");
            } else if (hour > 23) {
                System.out.println("Hier, auf der Erde, ist der Tag nach 23 Stunden und 59 Minuten vorbei. Bitte " +
                        "gewöhne dich daran.");
            }
        }
        while (hour<0 || hour >23);
```
Und die Minutenangabe war für die Aufgabe eigendlich gar nicht von nöten (und war 
ursprünglich auch gar nicht vorgesehen), aber ich habe sie benutz um mich weiter über 
die Dummheit des Users zu empören:
```java
if (minutes < 0) {
                System.out.println("Du sollst hier die Minuten angeben, nicht deinen Intelligenzquotienten!");
            } else if (minutes > 59) {
                System.out.println("Wenn deine Uhr " + minutes + " Minuten anzeigt, würde ich sie zurückgeben...");
            }
```
Alles in Allem also ganz einfach. 


Dann habe ich die Aufgabenliste entdeckt und mit der ersten Aufgabe:
#### Erzähl was über dich
begonnen. Da das eigendlich nur ein Kennenlernen der Variablenarten ist war das ganz
einfach (wieder bis auf das Datum, aber ich hab gehört, das kommt später noch genauer).

Anschließend wurde uns gesagt, dass wir die Aufgaben der Unit 2 nicht mehr machen müssen, weil wir schon so fortgeschritten sind. Also auf zur Unit 3:
#### Berechnung des Maximums
Ich habe damit begonnen, und Eingabe auslesen und in einen Array packen hat schon gut funktioniert. Für das Vergleichen der Array-Slots und speichern der größten Zahl habe ich schon Ideen, aber hatte ich keine Zeit mehr, sie Auszuprobieren. 

Außerdem haben wir uns heute Sortieralgorythmen angeschaut und einen einfachen gemeinsam programmiert. 

[33, 12, 5, -4, 8]

[-4, 12, 5, 33, 8]

[-4, 5, 12, 33, 8]

[-4, 5, 12, 8, 33]

            



# Erster Tag

Java programmieren wird noch sehr lustig.

Der Scanner: 
Scanner scanner = new Scanner(System.in);
        userInput = scanner.next(); 
       (oder userInput = scanner.nextInt();    )
  //userInput ist der Variablenname,
danach muss noch vor der VoidMain 
import java.util.Scanner;
auftauchen. kann man mit Alt+Enter einfügen.

Die Array sind praktisch aber kompliziert. 
        char[] singleLetter = userInput.toCharArray();
        char[] changedLetter = new char[userInput.length()];
        
Außerdem bin ich jetzt bei Git (und oder Github) und da werden sachen gespeichert
und/oder gecommitted. dabei soll man "Reformat" und noch was anhackerln

reformat 
commit and push

Man kann auch Charakter in Zahlen umwandeln und umgekehrt:
 int x = 'a';
        System.out.println(x);
        System.out.println((char) 97);
        
Wenn man mit "Rest" dividieren möchte brauch man den command %
zum Beispiel: 14 % 3 = 2
Die "Haupzahl" fällt weg, es bleibt nur der Rest übrig. Mit vergleichen ( && bzw || )
kann man dann gut weiterprogrammieren. 

Meine projekte liegen auf C:\Users\Thomas Witt\IdeaProjects