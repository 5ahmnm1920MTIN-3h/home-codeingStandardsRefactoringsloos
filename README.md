# home-codeingStandardsRefactoringsloos

## Home Refactoring-Project


---------
### Aufgabenstellung

Anlegen eines Repositories in der Organisation 

home-codeingStandardsRefactoring (inkl. README und gitignore)

Ausarbeitung Refactoring in README einfügen übersichtlich formatieren. 

Folgendes Unity Projekt einfügen (https://github.com/5ahmnm1920MTIN-3h/home-toRefac-SantaRun-smeerws), anschließend Refactoring durchführen (Clean Code lt. Coding Standards und Refactoring)

Das Refactoring sollte anhand der commit Messages nachvollziehbar sein! Bei mind. 3 Refactorings sollte der Testcase als kurze Beschreibung in den commit Messages dabei sein. Bitte diese Commits am Anfang incl. Testcase markieren.



Ausarbeitung Refactoring:

Was ist Refactoring Definition in eigenen Worten?

Welche Vorteile/Nachteile birgt Refactoring?

Was sind die Refactoring-Schritte?

Prinzipien von guten Code?

Was versteht man unter Code Smell?

Recherche von 10 Code Smells die Eure Projekt betreffen können, inkl. Beschreibung und Beispiel.

---------
### Development Platform

Unity version 2019.1.14f1
Visual Studio Community 2017
Mac Os Mojave Version 10.14.6

---------
### Ausarbeitung Refactoring:

#### Was ist Refactoring Definition in eigenen Worten?
Refoactoring ist die Kunst einen Code der unübersichtlich gecoded wurde zu überarbeiten und übersichtlich/verständlich zu formatieren.

#### Welche Vorteile/Nachteile birgt Refactoring?
Refactoring bringt den Vorteil dass sich jeder der den Code ansieht auskennen sollte und die Ladezeiten nicht so lange dauern da unnötiger Code eliminiert wird. Dazu kommt dass man bei weiteren Projekte den Code als "vorlage" verwenden kann (man kann den Code wiederverwerten).
Ein Nachteil ist der zusätzliche Zeitaufwand und dass man seinen Code wenn man nicht richtig Refactored "zerstörren" könnte.

##### Was sind die Refactoring-Schritte?
1. Variablen und Funktionen verständlich/logisch benennen. Variablen und Funktionen ohne "_" und mit CamelCase benennen.
2. Magical Strings
3. Funktionen nicht in Funktionen

#### Prinzipien von guten Code?
-> Sauberer Code ist leichter lesbar.
-> Andere Entwickler können ihn besser lesen und verstehen.
-> Klassen und Methoden sind auf die Erfüllung einer Aufgabe ausgerichtet und werden nicht durch Nebenaufgaben „verunreinigt“.
-> Die Abhängigkeiten zu anderem Code sind auf ein Minimum begrenzt.
-> Sauberer Code ist gut zu testen.
-> Es gibt keine Duplizierungen.
-> Der Code enthält keine Überraschungen.

#### Was versteht man unter Code Smell?
Code-Smell bezeichnet funktionierenden, aber schlecht struktuierten Quellcode.

#### Recherche von 10 Code Smells die Eure Projekt betreffen können, inkl. Beschreibung und Beispiel.
1. Code-Duplikate: Als Code-Duplikat wird Quellcode verstanden, der in identischer oder ähnlicher Form mehrfach innerhalb einer Software verwendet wird.
2. lange Methoden: Je länger eine Methode ist, desto fehleranfälliger ist sie. Zusätzlich erschweren lange Methoden die Wiederverwendung. Gerne wird auch von Spaghetti-Code gesprochen.
3. umfangreiche Parameterlisten: Sie erschweren das Verständnis von Methodenaufrufen, da Attribute von Objekten als Parameterliste übergeben werden, anstatt das Objekt an die Methode zu übergeben.
4. viele Änderungen an einer Klasse: Werden Klassen zu umfangreich, muss für eine Änderung eine Klasse häufig an mehreren Stellen angepasst werden.
5. temporäre Felder: Felder einer Klasse beschreiben die Zustände ihrer Objekte, wobei ein Objekt ein Feld nur unter bestimmten Umständen bzw. temporär verwendet, so dass der Code schwer zu verstehen ist.
6. wiederholende Switch-Anweisungen: Sie werden an mehreren Codestellen verwendet, obwohl es besser wäre, sie als eigene Methode zu extrahieren.
7. Kommentare: An sich sind Kommentare zwar gut, sie können aber auch Hinweise auf schlechten Code liefern, der durch den Kommentar verständlicher werden soll.
8. Lazy Class: Das Verstehen und Verwalten von Klassen kostet immer Zeit und Geld. Wenn eine Klasse nicht genug tut, um Ihre Aufmerksamkeit zu erregen, sollte sie gelöscht werden.
9. Middle Man: Wenn eine Klasse nur eine Aktion ausführt und Arbeit an eine andere Klasse delegiert, warum ist sie überhaupt vorhanden?
10. Data Clums: Manchmal enthalten verschiedene Teile des Codes identische Gruppen von Variablen (z. B. Parameter für die Verbindung mit einer Datenbank). Diese Gruppen sollten in eigene Klassen umgewandelt werden.
