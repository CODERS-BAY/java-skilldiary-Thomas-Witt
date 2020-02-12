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

            

