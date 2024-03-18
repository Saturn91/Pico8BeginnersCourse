<p align="center">
</br>
    </br>
    </br>
    </br>
    </br>
    </br>
    <img src="images/main.png" alt="Image description" style="max-width: 360px;"/>
    </br>
    </br>
    </br>
    Kursleiter: Manuel Geissberger
    </br>
    Datum: 02.04.2024
    </br>
    Thema: Kurs Spieleentwicklung mit Pico8
    <br>
    </br>
    </br>
</p>


<h1 align="center">
Spieleentwicklung mit Pico8 2024 / Saturn91
</h1>

<div style="page-break-after: always;"></div>

# Was ist Pico 8

<img src="images/intro/originalDescription.png">

(lose Übersetzung der englischen offiziellen Webseite (lexaloffle.com)[https://www.lexaloffle.com/pico-8.php])

    PICO-8 ist eine fantastische Konsole zum Erstellen, Teilen und Spielen von kleinen Spielen und anderen Computerprogrammen. Es fühlt sich an wie eine normale Konsole, läuft aber unter Windows/Mac/Linux. Beim Einschalten begrüßt dich das Gerät mit einer Kommandozeile, einer Reihe von Tools zur Erstellung von Cartridges und einem Online-Cartridge-Browser namens SPLORE.

## Pico8 starten
Wir verwenden heute die gratis online version von Pico8 die "Education" (oder zu Deutsch "Ausbildungs") version. Diese erlaubt uns das komplette Spiel zu erstellen und alle Featurees der Konsole zu verwenden, AUSSER das exportieren des Spiels als ".exe" file. Dies geht nur mit der bezahlten Version. Wer möchte kann sich am Ende des Tages bei mir melden und dann kann ich gerne dabei helfen eine Version zu erhalten.


<h2 align="center"> click me --> <a href="https://www.pico-8-edu.com/">Pico8-edu link</a> <-- click me
<br>
<br>
<div align="center">
<img  src="images/intro/pico8Edu.png" style="max-width: 300px;">
</div>

<div style="page-break-after: always;"></div>

## Fantasy Konsole?
<div align="center">
<img  src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Nintendo-Switch-Console-Docked-wJoyConRB.jpg/300px-Nintendo-Switch-Console-Docked-wJoyConRB.jpg">
</div>
Eine Konsole ist salop gesagt was du als Nintendo Switch und oder PS4 kennt. Ein Gerät mit dem du (in der Regel) nur Spiele spielen kannst. Vielleicht hast du schon einmal gehört, dass Konsolen auf dem Computer "emuliert" werden können. Für ältere Konsolen (Gameboys, Gamecube, Nintendo64 etc...) findet man online sogenannte "Emulatoren" die es erlauben alte Spiele (z.B. das erste Pokemon) auf dem Rechner zu spielen. Statt einen Emulatoren zu benutzen könnte man in diesem Fall aber auch einfach auf den Flohmarkt oder Ebay gehen und sich das Originalgerät kaufen. Dies sind "echte" Konsolen.

Eine Fantasy Konsole ist eine Konsole, für die es keine Hardware / Originalgeräte gibt. Es gibt nur den Emulator. Zep der Entwickler von Pico8 war ein grosser Fan vieler dieser Konsolen und hat sich mit Pico8 den Traum erfüllt selbst eine solche zu entwickeln.

## Komandozeile?
Komandozeilen kennst du vielleicht aus "Hacker" Filmen und Serien. Sobald man eine solche offen hat, kann man seine Eltern und Geschwister stark beindrucken :D.

### Hacker modus
Auf windos einfach einmal "cmd" + enter eintippen, dann in dem schwarzen Fenster dass sich öffnet:
1. `color 0A` eintippen (textfarbe auf grün umstellen)
2. `netstat -a` eintippen (hacker modus starten)
3. Zuschauer versichern dass das oben nur ein harmloses Anzeigen der IP adresse war (was auch der Wahrheit entspricht)

<div align="center">
<img  src="images/intro/cmd.png">
</div>

### Ok, Spass beiseite was ist eine Komandozeile
Komandozeilen sind die Basis unserer Betriebssysteme. Die ersten Computer waren nur mit Komandozeilen zu bedienen. Man kann mit Komandozeile einen Computer mindestens genau so gut bedienen wie mit der grafischen Oberfläche und der Maus.

Ein paar Operationen die man mit der Komandozeile machen kann:
1. Ordner erstellen
2. Files erstellen
3. Files kopieren
4. Computer herunterfahren
5. Netwerk einstellungen anzeigen
6. Versuchen herauszufinden ob mein Drucker mit meinem Netzwerk verbunden ist
7. ...

Wie gesagt im Prinzip alles was auch über die grafische Oberfläche möglich ist.

### Wie genau funktioniert die Kommandozeile in Pico8?
Sobald man auf (pico8-edu)[https://www.pico-8-edu.com/] den play button gedrückt hat, kommt man in die Komandozeile von pico8. In der Komandozeile können nun verschiedene Komandos benutzt werden. Unten nur ein paar Beispiele die wir heute noch brauchen werden.

1. `save mein_projekt` -> herunterladen des aktuellen projekts
2. `load` -> File eexplorer öffnen um bestehende Datei von der Festplatte zu laden
3. `load mein_projekt` -> öffnen der Datei "mein_projekt.p8" aus dem Download Ordner  

## Pico8 Spiele bibliothek Splore (nur gekaufte version)
Ein sehr interessanter Befehl ist `splore` der in pico8-edu leider nicht funktioniert. Mit diesem Befehl können die von aderen Usern programmierten Spiele gespielt werden.

Dieser Befehl erlaubt es dir Spiele anderer Entwickler herunter zu laden, zu spielen und ihren Code zu studieren / kopieren.

## Was kann Pico8 (und was nicht)
Pico8 ist eine moderne Game engine, die 8Bit systeme emuliert. Auf gut Deutsch, eine moderne Game engine die so tut als sei sie ein Computer der vor etwa 30 Jahren gebaut wurde.

Dass man mit einem 30 Jahren alten Computer kein Fortnite oder minecraft programmiert dürfte glaube ich klar sein. Lass uns aber mal anschauen was für Spiele mit Pico8 gemacht werden können.

| Screenshot | Beschreibung |
|:---:|:---:|
| ![Image1](https://www.lexaloffle.com/bbs/cposts/sa/satelite_catcher-6.p8.png) | Das Spiel was wir heute grösstenteils heute programmieren werden. Hier sehen wir das finale Produkt, dass ich an einem Wochenende erdacht und entwickelt habe. [Satelite Catcher](https://www.lexaloffle.com/bbs/?pid=94300#p) |
| ![Image2](https://www.lexaloffle.com/bbs/cposts/po/porklike-2.p8.png) | Ein 2D dungeon crawler. Zu diesem Spiel gibt es ein online tutorial dass einen Schritt für Schritt durch den Entwicklungsprozess führt. [porklike - spiel](https://www.lexaloffle.com/bbs/?pid=73825#p) / [pico8 roguelike -tutorial](https://www.youtube.com/watch?v=HnY7Inp74dw&list=PLea8cjCua_P3LL7J1Q9b6PJua0A-96uUS)|
| ![Image2](https://www.lexaloffle.com/bbs/cposts/ca/cab_ride-7.p8.png) | Ein pseudo 3D Ubahn simulator, der Entwickler dieses Spiel kennt Pico8 seit Jahren und ist ein profesioneller Entwickler, solche Projekte brauchen sehr viel Zeit! [cab-ride](https://www.lexaloffle.com/bbs/?pid=86966#p) |

Was haben diese Spiele gemeinsam?

## Pico8 Spezifikationen
1. Bidlschirmgrösse: 128x128
2. Grafiken: pixelart
3. Sound Effekte: einfache 8bit
4. Gesamtes Spiel mit code und grafik daten befindet sich in den oben sichtbaren "Cartridge" Bildern. 

Wie bereits angetönt, damit progammieren wir nicht dass nächste Fortnite, aber wir schaffen es in der Zeit die wir zur Verfügung haben tatsächlich ein Spiel zu programmieren.

Dann lass uns starten :D

# Lets start coding!
Nun starten wir mit dem Programmieren des Spiels.

## Vorwort
Beim Programmieren ist es wichtig, dass wir beinahe jeden Buchstaben und insbesondere Sonderzeichen exakt so kopieren wie es in diesem Tutorial vogegeben wird. Ich empfehle daher die Codebeispiele die in diesem Skript abgedruckt sind 1:1 zu kopieren (CTRL+C) und dann in Pico8 einzusetzen (CTRL+V). 

Sollte etwas nicht funktionieren wie im Script beschrieben, gerne entweder das Kapitel "Debugging / Fehlersuch" durchlesen, und oder mich um Hilfe fragen.

## print("hallo")
Als erstes schauen wir an wie wir in Pico8 programmieren. Dazu starten wir die Pico8-edu, oder wer hat die Vollversion.

<h4 align="center"> click me --> <a href="https://www.pico-8-edu.com/">Pico8-edu link</a> <-- click me</h4>
<br>
<br>
<div align="center">
</div>

1. Pico8 starten
2. (nur für pico8 edu) Play button drücken
3. Nachdem diie kurze Intro Animation abgespielt wurde sollte es wie auf dem bild unten ausehen. Evtl. seht ihr jedoch eine andere version (unten: ) die versions Unterschiede könnt ihr ignorieren. Auf der Edu version im Browser werdet ihr ausserdem zusätzlich einen pinken Teext "USING TEMPORARY DISK" sehen.

<div align="center">
<img  src="images/step-by-step/01_pico8_start.png" style="max-width: 300px;">
</div>

4. fange einmal an zu tippen und gib `print("hello world")` ein (beachte dass automatisch Grossbuchstaben verwendet werden... dies ist so bei Pico8, Grossbuchstaben (shift) werden in Pico8 zu "komischen" Zeichen) dann mit "Enter" bestätigen. Danach erscheint unten eine neue Zeile:

<div align="center">
<img  src="images/step-by-step/02_hallo.png" style="max-width: 300px;">
</div>

5. Wenn ihr eine Meldung "SYNTAX ERROR" seht, habt ihr einen Fehler gemacht, in der Regel habt ihr ein oder mehrere Zeichen vergessen zu tippen. In meinem Beispiel habe ich das `"` vor der Klammer vergessen. Auf jeden Fall solltet ihr Zeichen für Zeichen überprüfen ob ihr das richtige abgetippt habt.

<div align="center">
<img  src="images/step-by-step/03_syntax_error.png" style="max-width: 300px;">
</div>

6. Glückwunsch das war bereits die erste Zeile code die ihr in Pico8 habt laufen lassen.

### Aufgabe
1. was musst du tun um `hallo name` zu printen?
2. versuch mal absichtlich einen Fehler zu machen und überlege dir ob du die Fehlermeldung verstehst.

## a + b
Pico8 kann auch als Taschenrechner verwendet werden. Lass es uns versuchen.
1. tippe `a=1` + enter
2. tippe `b=2` + enter
3. tippe `c=a+b` + enter
4. tippe `print(c)` um das ergebnis zu auszugeben (auszudrucken englisch -> print)

Ergebnis:
<div align="center">
<img  src="images/step-by-step/04_a_and_b.png" style="max-width: 300px;">
</div>

### Aufgabe
1. Könnte man auch direkt die Rechnung im print ausgeben? Wie?
2. Hat jemand eine Idee wie man multiplikationen eingeben könnte?
3. Divisionen?
4. Minus?

## Weitere Kommandos
Die folgenden Kommandos bitte einmal ausprobieren.
| Kommando | erwarteter effekt |
| -- | -- |
| `cls` | Bildschirm leeren |
| `print("hallo",20,20,9)` | Hallo auf den Bildschirm schreiben print(text,x-Pos,y-Pos,farbe) |
| `rectfill(0,0,100,100,11)` | Rechteck auf den Bildschirm zeichnen rectfill(x-Pos1,y-Pos1,x-Pos2,y-Pos2,farbe)|
| `circ(80,80,40,1)` | Kreis zeichnen (circ(x-Pos,y-Pos,radius,farbe)) | 
| `circfill(40,40,40,2)` | Kreis füllen circfill(x-Pos,y-Pos,radius,farbe)|

## unser erstes Programm
Was wir in den vorherigen Abschnitt gemacht haben ist direkt mit der engine zu interagieren und ihr mit Programmier code zu sagen was sie tun soll. Das kann unter Umständen bereits nützlich sein, aber wir können die oben gemachten Beispiele noch effizienter implementieren.

Dafür werden wir nun erstmals in die Programmieransicht wechseln. 

Um zur Programmieransicht zu gelangen benutze die Taste "ESC" oben links auf der Tastatur.

<div align="center">
<img  src="images/step-by-step/05_editor.png" style="max-width: 300px;">
</div>

Wir schreiben nun unser erstes Programm. Dazu bitte folgendes abtippen. (Ja ihr könnt es auch kopieren)

```lua
cls(1)
circfill(30,30,40,2)
circfill(60,50,40,13)
rectfill(38,78,86,86,0)
print("let's pico8",40,80,11)
```

Dass sieht dann im Editoren so aus:
<div align="center">
<img  src="images/step-by-step/06_first_programm.png" style="max-width: 300px;">
</div>

Nun lassen wir das Programm einmal laufen. Dazu nutzen wir den Command:

CTRL + S (speichern)
CTRL + R (run)

Alternativ können wir auch mit "ESC" zurück in die Konsole gelangen. Dann mit den Commands "save" + ENTER und "run" + ENTER um das Programm zu starten.

Das Resultat sollte so ausehen.

<div align="center">
<img  src="images/step-by-step/07_first_prg_run.png" style="max-width: 300px;">
</div>

<br>
<br>

<p style="font-size: 32px; line-height: 35px">GRATULIERE DU HAST DEIN ERSTES PROGRAMM GESCHRIEBEN!!</p>

Gut, aber mit Micrsoft Powerpoint krieg ich dass auch hin... ist dass nicht ein wenig kompliziert? Ja, da hasst du recht. Aber lass uns ersteinmal die Zeilen auseinander nehmen bevor wir was interessanteres schreiben.

## Klassenaufgabe
1. in Pico8 den Code anschauen und mit den "Kommandos" von weiter oben vergleichen. Warum ist was wo?
2. Habt ihr eine Idee warum die Schrift über den Kreisen gezeichnet wird?

## Fazit
Mit verschiedenen Kommandos kann man einer Game engine sagen was sie tun / anzeigen soll. Mehrere Kommandos zusammen sind das was wir ein Programm nennen. Ein Computerspiel ist im Grunde genaus so ein Programm. Lass uns nun im nächsten Kapitel anschauen wie ein solches Computerspiel Programm aufgebaut ist.
<div style="page-break-after: always;"></div>

# Sprites oder "Bilder" zeichnen
Nun kommen wir zu einem sehr tollen Abschnitt. Ihr dürft nun die Grafiken zeichen die ihr für den Rest des Projekts verwenden möchtet.

<div align="center">
<img  src="images/step-by-step/08_spaceship.png" style="max-width: 150px;">
</div>

Um euer eigenes Raumschiff zu zeichnen könnt ihr in Pico 8 oben rechts im Editoren das Icon "Sprites" anclicken.

<div align="center">
<img  src="images/step-by-step/09_open_sprite_editor.png" style="max-width: 300px;">
</div>

Danach öffnet sich für euch der sogenannte Spriteeditor.


<div align="center">
<img  src="images/step-by-step/10_spriteeditor.png" style="max-width: 300px;">
</div>

Zeichnet nun folgende Dinge von links nach rechts:
1. euren Spieler character (Ein Raumschiff) in knalligen Farben
2. etwas zum Aufsammeln (in meinem Fall ein Satelit) ebenfalls knallig aber andere Farben als der Spieler
3. Ein paar hintergrund Objekte (in meinem Fall Sterne) in eher gedeckten Farben

Bei mir sieht dass dann so aus

<div align="center">
<img  src="images/step-by-step/11_sprites.png" style="max-width: 300px;">
</div>


<br>
<br>

> Nun werden wir einmal speichern was wir bis jetzt gemacht haben.
> Dazu einmal Escape drücken bis du die Konsole oder das Terminal siehst.
> Dort den Befehl "save meinspiel-sprites.p8" und dann ENTER drücken.
> Es sollte dann eine Datei "meinspiel-sprites.p8" gedownloaded werden.

> Laden funktioniert ähnlich. Um eine vorher heruntergeladene Version zu laden, gib einfach "load meinspiel.p8" ein und dein Spiel wird wieder geladen.

> Speicherort: Dateien können nur vom download ordner geladen werden und werden auch immer dort gespeichert. Andere Dateien findet Pico8 nicht.

<br>
<br>

## Sprites zeichnen mit Pico8
Nun wollen wir zumindest einmal das Spielsrpite zeichnen. 

1. geht wieder in die Konsole (oder Terminal) und gebt ein "spr(1,20,10)"
2. der Spieler wird oben links gezeichnet.
3. Welche werte musst du wohl ändern um den Spieler in der Mitte des Bildschirms zu zeichnen (Tipp, der Bildschirm von pico8 ist 128x128 gross, sprites sind 8x8 gross)

Das Endresultat sollte so ausehen

<div align="center">
<img  src="images/step-by-step/12_draw_player.png" style="max-width: 300px;">
</div>

Wenn du herausgefunden hast wie du das Sprite in der Mitte zeichnen kannst
1. Wechsle in den Code Editoren.
2. lösche allen bisherigen Code
3. Schreibe in der ersten Zeile `cls()` um den Bildschirm zu löschen 
4. füge nur den Command hinzu um das Sprite in der Mitte des Bildschirms zu zeichnen
5. Drücke `CTRL + S` (speichern) und `CTRL + R` (run) um das Programm zu starten. Du solltest dann das Sprite auch wieder in der Mitte des Bildschirms sehen.

```lua
cls()
spr(1,?,?) --? mit den werten für x und y ersetzen ;-)
```

Mit dieser Funktion können wir also Sprites auf den Bildschirm zeichnen.

# Variablen
Wenn wir einen Wert mehrfach benötigen, oder zischen speichern wollen, können wir beim Programmieren sogenannte Variabeln einsetzen. Wir werden variabeln nun verwenden um unseren Spieler auf dem Bildschirm zu positionieren. Dazu erstellen wir nun zwei variablen.

1. `player_x` die x Koordinate des Spielers
2. `player_y` die y Koordinate des Spielers

Im Code sieht dass wie folgt aus

```lua
--definieren der variabeln
player_x = 60 
player_y = 60

cls()

--benutzen der variabeln
spr(1,player_x,player_y)
```

> nicht vergessen den Code zu testen. Dazu wie immer `CTRL S` & `CTRL R` der Spieler sollte in der Mitte des Bildschirms angezeigt werden.

--> Nun bitte das Spiel wieder speicher und downloaden (in Terminal `save meinspiel-variabeln.p8`) <--

## Was man in variabeln speichern kann
Variabeln können viele verschiedene Werte speichern. Die einfachsten sind texte und zahlen. Diese werden wir in diesem Kurs am häufigsten verwenden.

```lua
ein_text = "hallo ich bin ein Text"
eine_zahl = 123

print(ein_text) --wird "hallo ich bin ein Text anzeigen"
print(eine_zahl) --wird "123" anzeigen
```

> Wir können den Wert von Variabeln auch ändern. Dies werden wir im nächsten Kapitel verwenden um den Spieler zu bewegen

# Konzept "Gameloop" oder Game schlaufe
In einem Spiel werden nicht nur Bilder angezeigt sondern es werden "bewegte" Bilder angezeigt. Ein vergleichbares Beispiel ist zum Beispiel ein Film.

## Klassenaufgabe
1. Wie genau kommen bewegte Bilder, oder Filme auf den Bildschirm. Geht davon aus dass ihr den Film von Hand zeichnen müsstet um die sache zu vereinfachen.
2. Wer hat schon einmal von 60 FPS gehört oder von `frames per second`

## Bewegung in Spielen
Um ein bewegtes Bild in Spielen darzustellen müssen wir ein Grafikelement (zum Beispiel ein Rechteck) nacheinander an verschiedenen Positionen zeichnen. Wir müssen Code mehrfach aufrufen. Dies wird bei Spielen mit der Game loop gemacht.

> !! Vergewissert euch dass ihr gespeichert und das Spiel als "mainspiel-variabeln.p8" gedownloaded habt.

Nun erweitert ihr euren Code wie folgt

```lua
--definieren der variabeln
player_x = 60 
player_y = 60

cls()

--benutzen der variabeln
spr(1,player_x,player_y)

counter = 0
function _draw()
    counter = counter + 1
    --fuege "hello " und counter zusammen (z.B. "hello 0")
    print("hello "..counter)
end
```

## Klassenaufgabe:
1. lasst das Programm laufen
2. was seht ihr
3. habt ihr eine Vermutung was der neue Teil im Code macht?
4. warum sehen wir den Spieler am Anfang, aber nur kurz?

## update und draw Funktionen
Wir haben im letzten Kapitel bereits die Funktion `_draw` benutzt die mit 30fps aufgerufen wird. Das heisst 30 mal die Sekunde. Es gibt neben `_draw` noch zwei weitere Funktionen.

1. _init (läuft am anfang einmal)
1. _draw (auf den Bildschirm zeichnen)
2. _update (hier findet unsere Gamelogik statt)

Diese drei Funktionen zusammen können unseren ganzen Spiele code beinhalten. Im folgenden werden wir sie dazu brauchen um unseren Spieler zu bewegen.

## Schritt für Schritt zum bewegten Spieler
1. lösche allen Code der momentan im Code editoren ist.
2. Als erstes definieren wir wieder die beiden Variabeln für die Spieler position. Beachte dass wir sie dieses mal mit dem Wert 0 initialisieren.
```lua
player_x = 0 
player_y = 0
```
3. Nun verwenden wir darunter die `_init` funktion um den Spieler in die Mitte des Bildschirms zu setzen.
```lua
function _init()
 player_x = 60
 player_y = 60
end
```
4. Als nächstes fügen wir die `_update` funktion hinzu mit dem Code der den Spieler in X richtung (nach rechts) bewegen wird
```lua
function _update()
 player_x = player_x + 1
end
```
5. Schlussendlich fehlt noch unsere altbekannte `_draw` funktion
```lua
function _draw()
 cls()
 spr(1,player_x,player_y)
end
```
6. Was erwartet ihr passiert nun wenn ihr das Spiel laufen lasst?
7. finden wir es mit `CTRL + S` und `CTRL + R` heraus.

>Falls ihr einen Fehler bekommt oder sich der Spieler nicht bewegt, vergleicht einmal den Code unten mit eurem. Zum besseren Verständniss habe ich mit `--` kommentare hinzugefügt. Dass sind Texte die Pico8 ignoriert und die irh verwenden könnt um Notizen in eurem Code zu haben und Dinge (für später?) zu dokumentieren.

>Tipp in meinem aktuellen Steam Spiel befinden sich ganz viele Kommentare die mir schon oft das Leben gerettet haben ;-)

```lua
player_x = 0 
player_y = 0

--diese function laeuft am anfang des spiels einmal durch
function _init()
 player_x = 60
 player_y = 60
end

--diese function wird abwechslungsweise mit _draw 30 mal pro sekunde ausgefuehrt
function _update()
 player_x = player_x + 1 --vergroessere x um 1 mit jedem frame
end

--diese function wird abwechslungsweise mit _update 30 mal pro sekunde ausgefuehrt
function _draw()
 cls() --bildschirm leeren
 spr(1,player_x,player_y)
end
```

# Tastatur input
Wir wissen nun wie wir unseren Spieler bewegen können. Die Bewegung ist zugegebenermassen ein wenig langweillig. Was fehlt ist dass wir den Spieler kontrollieren können. Wir brauchen Informationen welche Tasten unser (menschlicher) Spieler betätigt. Lass uns doch kurz anschauen welche Taste wir bei Pico8 zur verfügung haben.

Hier möchte nun zum ersten mal auf das Pico8 Cheatsheet (zu deutsch Spickzettel) hinweisen in dem die wichtigsten Befehle und Funktionen der Engine aufgelistet sind. 

Online findet ihr diesen Spickzettel hier <h4 align="center"> click me --> <a href="https://www.lexaloffle.com/bbs/?tid=28207">Cheat sheet</a> <-- click me</h4>. Ich habe jedoch auch eine Kopie auf der online version dieses Scripts hinzugefügt. Im folgenden werde ich jeweils jene Auschnitte abbilden die wir gerade benötigen.

<div align="center">
<img  src="images/step-by-step/13_controlls.png" style="max-width: 300px;">
</div>

Wir sehen hier zwei Funktionen

- btn(...) `button (down)` (ist immer "true" wenn der Button lange gedrückt wird)
- btnp(...) `button pressed` (wird nur einmal kurz "true" sein)

Oben sehen wir welche Taste für was benutzt wird.

```lua
local up = btn(2)       --Pfeiltaste ^
local left = btn(0)     --Pfeiltaste > 
local down = btn(3)     --Pfeiltaste v
local right = btn(4)    --Pfeiltaste >

local buttonO = btn(4)  --"C" auf der Tastatur
local buttonX = btn(5)  --"X" auf der Tastatur
```

lass uns dass einmal testen. Dazu könnt ihr getrost den Code in eurem Programm nocheinmal überschreiben ;-)

```lua
--diese funktion einfach mal kopieren ;-)
function print_input(name,btnId)
    if btn(btnId) then 
        print(name..": true")
    else
        print(name..": false")
    end
end

function _draw()
    cls()
    print_input("up",2)
    print_input("left",0)
    print_input("down",3)
    print_input("right",1)

    print_input("C",4)
    print_input("X",5)
end

--kein _update und keine _init function!!!
```

Wenn ihr alles richtig kopiert hat sollte das laufende Programm so aussehen (in meinem Beispiel sind eine Pfeiltaste und X gerade gedrückt).

<div align="center">
<img  src="images/step-by-step/14_btn_visualiser.png" style="max-width: 300px;">
</div>

Nun was macht dieser Code genau? Lass ihn uns einmal genauer unter die Lupe nehmen.

Ich habe da ein wenig vorgegriffen und eine Funktion implementiert. Funktionen sind Programmcode den wir mehrmals verwenden möchten. Vorweg könnt ihr den Teil einmal ignorieren, was Funktionen genau sind und wie man sie verwendet werrden wir im nächsten Kapitel genauer anschauen.

## Die Input Funktion btn / btnp

Die Funktion btn lässt uns auslesen ob eine der verfügbaren Tasten gedrückt ist. Wir werden dass nun an einem einfacheren beispiel zeigen.

Dazu brauchen wir einen kurzen Einblick in boolsche Variabeln. Zu deutsch Variabeln die entweder 0 oder 1, ja / nein, oder im Progammierumfeld auch "TRUE" oder "FALSE" genannt (zu deutsch Wahr/Falsch). 

Wenn ich jetzt einen von euch Frage ob er gerade die Taste X auf seinem Laptop drückt, wird er mir mit ja oder nein antworten - und nein vielleicht ist keine plausible Antwort ;-).

Das gleiche macht die Funtion btn. Lass uns mal sehen wie das im code aussieht.

Das unten ist wieder ein minimalistisches Beispiel.

```lua
function _update()
 print(btn(5)) --x taste
end
```

Wenn wir dieses laufen lassen wird pico8 immer false anzeigen, ausser wenn wir die X Taste gedrückt haben. Dann wird true angezeigt.

>Fazit: die Funtion btn(5) fragt "den Computer" ob die Taste X gedrückt worden ist

## Den Spieler mit den Pfeiltasten bewegen
Wie im vorherigen Kapitel gelernt, können wir mit btn abfragen ob Tasten gedrückt sind. Um die Pfeiltasten abzufragen können wir laut Pico8 Cheat sheet die Adressen 0-3 abfragen.

Wir wissen nun wie wir diese Information erlangen können. Was noch fehlt ist wie wir dem Computer sagen sollen was er mit dieser Funktion anfangen soll. 

Denken wir uns einmal in folgende Lage hinein. Wir haben zwei Schüler Karli und Lotti. Karli steht mit dem Rücken zu Lotti, Lotti hat eine Tatatur in der Hand. Nun sollen Lotti und Karli unser Programm simulieren.

Lotti wird auf der Tastatur eine der Pfeiltasten drücken. Lotti darf aber nichts sagen ausser ja und nein. 

Wie kann nun Karli wissen welche der Tasten betätigt wurde? 

Karli muss Lotti fragen: "..." Lotti -> Nein / Ja

> lass uns zusammen mal eine Antwort finden

So bei unserem Computer ist es genau gleich. Ein Programm kann nicht wissen was für eine Taste benutzt wird wenn es den Computer nicht fragt ob die Taste gedrückt ist oder nicht. Unsere Funktion btn(5) ist diese Frage für die Taste "X".

Nun wenn Karli wissen möchte wohin er sich bewegen soll muss er für alle Richtungen fragen: 

1. "ist die Pfeiltaste - hoch gedrückt"
2. "ist die Pfeiltaste - link gedrückt"
3. "ist die Pfeiltaste - unten gedrückt"
4. "ist die Pfeiltaste - rechts gedrückt"

Und dann WENN eine der Taste gedrückt ist, bewegt sich Karli in die Richtung.

Dass heisst in unserer _update Funktion formulieren wir jetzt einmal diese vier Fragen. Aber da wir nur die Fragen stellen wird noch nichts passieren ;-).

```lua
function _update()
    local up = btn(2)       --Pfeiltaste ^
    local left = btn(0)     --Pfeiltaste > 
    local down = btn(3)     --Pfeiltaste v
    local right = btn(4)    --Pfeiltaste >
end
```

## Das Programmatische WENN (if)
Wir wenden uns nun einer sehr mächtigen grund Operation im Programmieren zu und zwar `if` englisch für "WENN". Ich gebe euch einmal ein Beispiel.

```lua
local myVariable1 = true
local myVariable2 = false

if myVariable1 then
 print("variable 1")
end

if myVariable2 then
 print("variable 2")
end
```

> Was denkt ihr wird von unserem Programm ausgegeben wenn wir dass laufen lassen.

a) "variable 1"

b) "variable 2"

c) "variable 1" gefolgt von "variable 2"


> Und nun wo wir wissen was, warum?

Mit der `if` Operation können wir Code laufen oder nicht laufen lassen WENN Bedingungen erfüllt oder eben nicht erfüllt sind.

Kommen wir noch einmal zurück zu unserem Beispiel mit Lotti und Karli. 
- Karli möchte wissen WENN er laufen darf
- Karli fragt ob Btn "up" gedrückt ist, WENN der gedrückt wäre dürfte er laufen oder?

Dann schauen wir uns doch einmal folgenden Code an.

```lua
local playerX = 0
local playerY = 0

function _init()
 playerX = 64
 playerY = 64
end

function _update()
 local up = btn(2)
 local left = btn(0)
 local down = btn(3)
 local right = btn(1)

 if up then
  --TODO move player up
 end

 if left then
  --TODO move player left
 end

 if down then
  --TODO move player down
 end

 if right then
  --TODO move player right
 end
end

function _draw()
 cls()
 spr(1,playerX,playerY)
end

```

> basierend auf obigem Code und dem Wissen dass wir bereits haben... wie bewegen wir nun den Spieler nach rechts wenn die Taste "right" gedrückt wurde?

## Lösung
Im folgenden erweitern wir unseren bisherigen Code soweit, dass der Spieler sich komplett in alle 4 Richtungen bewegen kann.


```lua
local playerX = 0
local playerY = 0

function _init()
 playerX = 64
 playerY = 64
end

function _update()
 local up = btn(2)
 local left = btn(0)
 local down = btn(3)
 local right = btn(1)

 if up then
  playerY = playerY -1
 end

 if left then
  playerX = playerX -1
 end

 if down then
  playerY = playerY +1
 end

 if right then
  playerX = playerX +1
 end
end

function _draw()
 cls()
 spr(1,playerX,playerY)
end

```

Dass ist jetz noch ein wenig langsam, wir können jetzt noch eine Geschwindigkeitsvariable `speed` einbauen die die Geschiwndigkeit des Spielers vorgibt.

Wir fügen also oben eine Variable `speed` hinzu und setzen sie auf 2

```lua
local speed = 2
```

> wo müssen wir diese Variabel nun hinzufügen?

# Funktionen allgemein
Im nächsten Kapitel werden wir anfangen unser nächstes Feature einzubauen. Den Sateliten, den es einzusammeln gilt. bevor wir dass aber machen möchte ich euch das Konzept von Funktionen näher bringen, so dass wir unseren Code ein wenig besser aufräumen können.

Lass uns wieder einmal ein Stück code anschauen.

```lua
--funktion definieren
function sayHello()
 print("hello")
end

--funktion verwenden
sayHello()
```

> Was denkt ihr macht dieser Code?

Eine Funktion kann verwendet werden um ein Codestück zu "verpacken" so dass man es an einer anderen Stelle wieder verwenden kann. 

Im obigen Beispiel macht dass noch nicht allzu viel Sinn, lass uns nun ein Beispiel anschauen bei dem das mehr Sinn ergibt. Interessant wird es nämlich wenn wir anfangen Parameter zu übergeben.

```lua
function sayHello(name)
    print("hello "..name)
end

sayHello("manuel")
sayHello("lotti")
sayHello("karli")
```

> Wie sieht das Resultat dieses Programm code aus?



<div align="center">
<img  src="images/step-by-step/15_functions_with_params.png" style="max-width: 300px;">
</div>

Wir können also Funktionen Parameter zu übergeben, um den selben code mit verschiedenen Werten laufen zu lassen. Dies werden wir später noch benötigen.

## Wir räumen auf!
Wir werden jetzt Funtionen verwenden um unseren Code ein wenig aufzuräumen.
Das Ziel ist es dass all unser "Player" code in einem eigenen File sein wird.

Um ein neues File zu erstellen stellt sicher dass ihr wieder im Editoren seid.

Nun ersetzen wir allen code den wir haben mit dieser leeren Vorgabe.

```lua
--main

function _init()

end

function _update()

end

function _draw()

end
```

>beachtet dass auch die hier bekannten 3 Funktionen eben Funktionen sind! Sie müssen aber nicht von uns aufgerufen werden, sondern pico8 macht das für uns. `_init` einmal am Anfang und dann abwechselnd `_update` und `_draw`

>beachtet auch den Kommentar `--main` dieser muss ganz oben stehen, er definiert den "Namen" unserer momentanen Datei. Dies wird euch später helfen zu identifizieren welcher Code wohin kommt.

### Die Player Datei
Nun fügen wir ein neues "Tab" oder eine neue "Datei" hinzu. Betätigt dazu dass kleine plus ganz oben.

<div align="center">
<img  src="images/step-by-step/16_add_new_tab.png" style="max-width: 300px;">
</div>

Danach solltest du ein neues leeres Tab sehen `1` sehen.

<div align="center">
<img  src="images/step-by-step/17_new_empty_tab.png" style="max-width: 300px;">
</div>

Wir kopieren folgenden Code in dieses Tab hinein. Vieles davon dürfte euch bereits bekannt vorkommen.

```lua
--player
local playerX = 0
local playerY = 0
local playerSpeed = 2

function init_player()
 playerX = 64
 playerY = 64
end

function update_player()
 local up = btn(2)
 local left = btn(0)
 local down = btn(3)
 local right = btn(1)

 if up then
  playerY = playerY - playerSpeed
 end

 if left then
  playerX = playerX - playerSpeed
 end

 if down then
  playerY = playerY + playerSpeed
 end

 if right then
  playerX = playerX + playerSpeed
 end
end

function draw_player()
 cls()
 spr(1,playerX,playerY)
end
```

>beachte auch hier wieder den Kommentar `--player` ganz oben

Wenn ihr nun alles richtig gemacht habt solltet ihr nun wenn ihr nun die Maus über die beiden Tabs bewegt, jeweils ein Anzeige sehen die euch den Inhalt der beiden obersten Kommentare "player" und "main" anzeigt. Damit könnt ihr später schnell herausfinden wo ihr welchen Code finden könnt. Wie schon einmal erwähnt, Kommentare machen euch das Leben einfacher.

<div align="center">
<img  src="images/step-by-step/18_hover_tab.png" style="max-width: 300px;">
</div>

Dieser Code wird nun noch nicht funktionieren. Wir müssen den Spielercode noch verwenden. Genau genommen müssen wir die drei Funktionen `init_player` `update_player` und `draw_player` noch aufrufen.

> Wo müssen wir die drei Funktionen im Player file wohl aufrufen?

### Das neue main file
```lua
--main

function _init()
 init_player()
end

function _update()
 update_player()
end

function _draw()
 draw_player()
end
```

## Fazit Funktionen
> Funktionen sind code den man mehrmals aufrufen kann

> Funktionen erlauben es uns den Code aufzuräumen

> Funktionen können Parameter übernehmen die man in der Funktion verändern kann

# zufällige Position

# Kollision

# SFX

# Punkte und UI

# Main menu

# Highscore

# Explosionen (Bonus Kapitel)

# Hintergrund (Bonus Kapitel 2)

## Pico8 Cheatsheet (Spickzettel)

## Wie Weiter?

## Debugging / Fehlersuche
 