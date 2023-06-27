# Lern-Bericht

Grapefruit: Angelov Angel und Keaunu Koelewijn

## Einleitung

Wir haben eine Website erstellt, die anderen Schülern, die an der IMS sind und Informatik lernen möchten, bei der Lösung ihrer Probleme helfen kann. Wir bieten Hilfe für Probleme in C#, Robocode, WinForms, Projektdokumentation und Lernbericht an.

## Was haben wir gelernt?

In unserem Projekt haben wir gelernt, wie man mit HTML und CSS eine Codebox erstellt, die ausfahrbar ist um Code snippets darzustellen.

## Beschreibung

Der HTML Teil des COdes definiert das Verhalten der Schaltfläche und des Bereichs dür den "Code-Snippet"" und die "Code Erklärung". Die Schaltfläche wird durch eine Checkbox erstellt.

```html
<input type="checkbox" id="fixed-button-checkbox">
```

Wenn das Kontrollkästchen aktiviert ist (also angeklickt wurde), wird der darunter liegende Bereich sichtbar. Die Schaltfäche selber wird durch das Label Element, das mit der checkbox verbunden (durch das "for" Attribut) ist genutzt. Die Klasse "fixed-butten" wurde zum Label deklariert um im CSS darauf zugreifen zu können.

```html
<label class="fixed-button" for="fixed-button-checkbox">Code</label>
```



Der Bereich für den Code und die Code-Erklärung werden in einem Container namens "slide-in" definiert. Im CSS wird dieser Container standardmässig ausserhalb des sichtbaren Bereichs platziert (rechts ausserhalb des Bildschirms). Wenn die Checkbox aktiviert wird, indem man auf das Label "Code" klickt, wird der Container mit einer seitlichen Animation (von rechts nach links) eingeblendet. Der Code selbst wird mit dem Code-Snippet-Element angezeigt. Darunter befindet sich ein Text, der den Code erklärt.

Um sich nicht zu verwirren kann man sich merken "class" Klassen sind  die selber definiert werden um später im CSS die optische darstellung zu optimieren.

* ```<div>``` ist ein Container mit dem man alle Elemente darin ansprechen kann.

* ```<code>``` ist das Code Snippet ELement.

* ```<p>``` wird verwendet um Text anzuzeigen.

```html
<div class="slide-in">
            <div class="code-snippet">
                <div class="snippet">
                    <code>
                        In diesem Abschnitt werden verschiedene Codes präsentiert.
                    </code>
                </div>
            </div>
            <div>
                <p class="snippet-explanation">Hier würde dann die Erklärung des entsprechenden Codes stehen.</p>
            </div>
        </div>
```



Im CSS-Code wird dann das Aussehen entsprechend definiert, wo und wie das Element aussehen soll. Zuerst wird die Checkbox unsichtbar gemacht, behält aber ihre Funktion. Die Hintergrundfarbe, Höhe und Breite des Containers "slide-in" werden im CSS definiert. Der Container wird am Bildschirm fixiert, damit der Benutzer den Code-Snippet immer ausfahren kann. Die Animation wird definiert, einschliesslich der Position vor und nachdem die Checkbox aktiviert wurde. Dadurch kann eine einfache Animation erstellt werden, wie im folgenden Beispiel:

```css
#fixed-button-checkbox {
    /* Checkbowird Unsichtbar gemacht. */
}

.fixed-button {
    /* Farbe, grösse, Animation und Position wird definiert. */
}

.slide-in {
    /* Farbe, grösse, Animation und Position wird definiert. */
}

.code-snippet {
    /* Farbe und grösse wird definiert. */
}

.snippet-explanation {
    /* grösse wird definiert. */
} 

```

(Mit HTML und CSS kann man seine eigene Kreativität ausleben, und es gibt verschiedene Arten, ein Problem zu lösen. Die vorherige Beschreibung war eine vereinfachte Erklärung, wie wir das Problem gelöst haben. Für den genauen Code kann man hier den HTML-Code für die Indexseite finden: [Html Code zu Index](https://github.com/Kurizaki/LA1600/blob/main/index.html), und hier den CSS-Code für die Webseite: [CSS Code zur Webseite](https://github.com/Kurizaki/LA1600/blob/main/style.css).)



Am Ende sieht diese Funktion auf unserer Webseite dann wie folgt aus:
![grafik](https://github.com/Kurizaki/LA1600/assets/110892283/15bc65c5-e97e-47a8-87e0-2cdb45a8b8d5)




## Verifikation

* Quelle 1: Der Text wurde selbst verfasst, um das Gelernte zu erklären.

* Quelle 2: Code-Snippets wurden aus eigenem Code ausgewählt, angepasst und für den Lernbericht verwendet, um die Umsetzung zu erklären.

* Quelle 3: Das Bild wurde von der eigenen Webseite übernommen, um zu veranschaulichen, was in diesem Lernbericht erklärt wurde.

# Reflektion zum Arbeitsprozess

**Was lief gut** :

Die Idee für die Webseite motivierte einige Mitglieder, schnell und effizient zu arbeiten, da das Ziel darin bestand, eine ästhetisch ansprechende Webseite zu erstellen. Dies beschleunigte den Arbeitsprozess erheblich.

**Was lief nicht gut** :
Während des Projekts haben zwei unserer Mitglieder wenig Einsatz gezeigt, obwohl sie daran erinnert wurden, ihren Code rechtzeitig fertigzustellen. Leider kam ihre Arbeit Wochen zu spät, wodurch einige Aufgaben doppelt erledigt wurden, da zu diesem Zeitpunkt ein zuverlässigeres Teammitglied die Aufgabe übernommen hatte. Ab einem bestimmten Zeitpunkt gab es fast keine Kommunikation mehr oder einige Mitglieder meldeten sich nicht, was dazu führte, dass wir die Webseite leider nicht rechtzeitig fertigstellen konnten.

**VBV** :
Um dieses Problem in Zukunft zu vermeiden, wäre es ratsam, dass sich das Team besser abspricht. Dazu gehört beispielsweise, sich im Voraus abzumelden, Termine abzusagen oder um Hilfe zu bitten. Wenn einem das Projekt nicht gefällt, sollte man ehrlich seine Meinung äussern und mit den Teammitgliedern besprechen, woran man arbeiten kann.



