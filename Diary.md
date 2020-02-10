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