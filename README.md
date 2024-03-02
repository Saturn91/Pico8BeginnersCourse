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
    Thema: Einsteiger Kurs Pico8
    <br>
    </br>
    </br>
</p>


<h1 align="center">
Pico8 Anfänger Kurs 2024 / Saturn91
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

## Komandos zum interagieren mit der Engine

## Debugging / Fehlersuche
 