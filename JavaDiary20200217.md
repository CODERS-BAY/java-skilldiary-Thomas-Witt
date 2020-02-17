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