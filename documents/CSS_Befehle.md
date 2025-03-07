# Die wichtigsten CSS Befehle

| CSS-Befehl | Beschreibung | Anwendungsbeispiel |
|-----------------------|------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| `color` | Legt die Textfarbe fest. | `color: red;` |
| `background-color` | Legt die Hintergrundfarbe eines Elements fest. | `background-color: blue;` |
| `width` | Bestimmt die Breite eines Elements. | `width: 100px;` |
| `height` | Bestimmt die Höhe eines Elements. | `height: 200px;` |
| `margin` | Legt den Außenabstand eines Elements fest. | `margin: 10px;` |
| `padding` | Legt den Innenabstand eines Elements fest. | `padding: 10px;` |
| `border` | Definiert den Rahmen eines Elements. | `border: 1px solid black;` |
| `font-size` | Bestimmt die Schriftgröße. | `font-size: 16px;` |
| `font-family` | Legt die Schriftart fest. | `font-family: Arial, sans-serif;` |
| `font-weight` | Bestimmt die Dicke der Schrift. | `font-weight: bold;` |
| `text-align` | Legt die horizontale Ausrichtung des Textes fest. | `text-align: center;` |
| `line-height` | Bestimmt den Zeilenabstand. | `line-height: 1.5;` |
| `display` | Definiert, wie ein Element angezeigt wird (z.B. `block`, `inline`). | `display: block;` |
| `position` | Bestimmt die Positionierungsmethode eines Elements (z.B. `absolute`, `relative`). | `position: absolute;` |
| `top` | Bestimmt den oberen Abstand eines positionierten Elements. | `top: 10px;` |
| `right` | Bestimmt den rechten Abstand eines positionierten Elements. | `right: 10px;` |
| `bottom` | Bestimmt den unteren Abstand eines positionierten Elements. | `bottom: 10px;` |
| `left` | Bestimmt den linken Abstand eines positionierten Elements. | `left: 10px;` |
| `z-index` | Bestimmt die Stapelreihenfolge eines positionierten Elements. | `z-index: 10;` |
| `overflow` | Bestimmt, wie überlaufender Inhalt behandelt wird (z.B. `hidden`, `scroll`). | `overflow: hidden;` |
| `visibility` | Legt fest, ob ein Element sichtbar ist oder nicht. | `visibility: hidden;` |
| `opacity` | Bestimmt die Transparenz eines Elements. | `opacity: 0.5;` |
| `background-image` | Legt ein Hintergrundbild fest. | `background-image: url('image.jpg');` |
| `background-repeat` | Bestimmt, ob und wie ein Hintergrundbild wiederholt wird. | `background-repeat: no-repeat;` |
| `background-size` | Bestimmt die Größe des Hintergrundbildes. | `background-size: cover;` |
| `background-position` | Bestimmt die Position des Hintergrundbildes. | `background-position: center;` |
| `border-radius` | Legt die Rundung der Ecken eines Rahmens fest. | `border-radius: 10px;` |
| `box-shadow` | Fügt einem Element einen Schatten hinzu. | `box-shadow: 2px 2px 5px grey;` |
| `text-shadow` | Fügt einem Text einen Schatten hinzu. | `text-shadow: 1px 1px 2px black;` |
| `float` | Bestimmt, ob ein Element links oder rechts schwebt. | `float: left;` |
| `clear` | Verhindert, dass ein Element neben einem schwebenden Element platziert wird. | `clear: both;` |
| `cursor` | Bestimmt den Mauszeiger, der angezeigt wird, wenn er über ein Element bewegt wird. | `cursor: pointer;` |
| `transition` | Definiert die Übergangseffekte zwischen zwei Zuständen eines Elements. | `transition: all 0.3s ease;` |
| `transform` | Ermöglicht die Transformation eines Elements (z.B. drehen, skalieren). | `transform: rotate(45deg);` |
| `animation` | Definiert Animationen für ein Element. | `animation: mymove 5s infinite;` |
| `content` | Fügt Inhalt vor oder nach einem Element ein (nur bei `::before` und `::after`). | `content: 'Hello';` |
| `list-style` | Bestimmt die Art der Aufzählungszeichen in Listen. | `list-style: none;` |
| `list-style-type` | Bestimmt den Typ der Aufzählungszeichen in Listen. | `list-style-type: square;` |
| `list-style-position` | Bestimmt die Position der Aufzählungszeichen in Listen. | `list-style-position: inside;` |
| `list-style-image` | Bestimmt ein Bild als Aufzählungszeichen in Listen. | `list-style-image: url('bullet.png');` |
| `table-layout` | Bestimmt das Layout einer Tabelle. | `table-layout: fixed;` |
| `border-collapse` | Bestimmt, ob Tabellenränder zusammenfallen oder getrennt sind. | `border-collapse: collapse;` |
| `border-spacing` | Bestimmt den Abstand zwischen den Rändern von Tabellenzellen. | `border-spacing: 10px;` |
| `caption-side` | Bestimmt die Position der Tabellenüberschrift. | `caption-side: top;` |
| `empty-cells` | Bestimmt, ob leere Tabellenzellen angezeigt werden. | `empty-cells: show;` |
| `quotes` | Bestimmt die Art der Anführungszeichen. | `quotes: "“" "”";` |
| `counter-reset` | Setzt einen Zähler zurück. | `counter-reset: section;` |
| `counter-increment` | Erhöht einen Zähler. | `counter-increment: section;` |
| `resize` | Bestimmt, ob ein Element von der Benutzerin/Benutzergröße geändert werden kann. | `resize: both;` |
| `object-fit` | Bestimmt, wie der Inhalt eines Ersetzungs-Elements (z.B. `https://dev1-fcn.dekager.dekabank.intern/odf/dekagpt/chat`) skaliert wird. | `object-fit: cover;` |
| `object-position` | Bestimmt die Position des Inhalts eines Ersetzungs-Elements. | `object-position: center;` |
| `clip-path` | Definiert einen Bereich, der sichtbar ist, der Rest wird abgeschnitten. | `clip-path: circle(50%);` |
| `filter` | Fügt grafische Effekte wie Unschärfe oder Farbverschiebung hinzu. | `filter: blur(5px);` |
| `backdrop-filter` | Fügt grafische Effekte auf den Hintergrund eines Elements hinzu. | `backdrop-filter: blur(10px);` |
| `mix-blend-mode` | Bestimmt, wie der Inhalt eines Elements mit dem Hintergrund gemischt wird. | `mix-blend-mode: multiply;` |
| `isolation` | Bestimmt, ob ein Element eine neue Stacking-Kontext erzeugt. | `isolation: isolate;` |
| `will-change` | Gibt an, welche Eigenschaften eines Elements sich ändern werden. | `will-change: opacity;` |
| `perspective` | Bestimmt die Perspektive für 3D-Transformationen. | `perspective: 1000px;` |
| `perspective-origin` | Bestimmt den Ursprung der Perspektive für 3D-Transformationen. | `perspective-origin: center;` |
| `backface-visibility` | Bestimmt, ob die Rückseite eines Elements sichtbar ist, wenn es gedreht wird.| `backface-visibility: hidden;` |
| `user-select` | Bestimmt, ob der Inhalt eines Elements ausgewählt werden kann. | `user-select: none;` |
| `pointer-events` | Bestimmt, ob ein Element Mausereignisse empfängt. | `pointer-events: none;` |
| `writing-mode` | Bestimmt die Schreibrichtung des Textes. | `writing-mode: vertical-rl;` |
| `text-orientation` | Bestimmt die Ausrichtung des Textes in vertikalen Schreibmodi. | `text-orientation: mixed;` |
| `text-overflow` | Bestimmt, wie überlaufender Text angezeigt wird. | `text-overflow: ellipsis;` |
| `white-space` | Bestimmt, wie Leerzeichen behandelt werden. | `white-space: nowrap;` |
| `word-break` | Bestimmt, wie Wörter gebrochen werden. | `word-break: break-all;` |
| `word-spacing` | Bestimmt den Abstand zwischen Wörtern. | `word-spacing: 5px;` |
| `letter-spacing` | Bestimmt den Abstand zwischen Buchstaben. | `letter-spacing: 2px;` |
| `text-transform` | Bestimmt die Groß-/Kleinschreibung des Textes. | `text-transform: uppercase;` |
| `text-indent` | Bestimmt den Einzug der ersten Zeile eines Textblocks. | `text-indent: 20px;` |
| `text-decoration` | Bestimmt die Textdekoration (z.B. Unterstrichen, Durchgestrichen). | `text-decoration: underline;` |
| `text-decoration-color` | Bestimmt die Farbe der Textdekoration. | `text-decoration-color: red;` |
| `text-decoration-style` | Bestimmt den Stil der Textdekoration (z.B. durchgezogen, gepunktet). | `text-decoration-style: dotted;` |
| `text-decoration-line` | Bestimmt die Linie der Textdekoration (z.B. Unterstrichen, Durchgestrichen).| `text-decoration-line: overline;` |
| `text-align-last` | Bestimmt die Ausrichtung der letzten Textzeile. | `text-align-last: left;` |
| `text-justify` | Bestimmt die Justierung des Textes. | `text-justify: inter-word;` |
| `hyphens` | Bestimmt, ob Wörter am Zeilenende getrennt werden. | `hyphens: auto;` |
| `tab-size` | Bestimmt die Breite eines Tabulators. | `tab-size: 4;` |
| `quotes` | Bestimmt die Art der Anführungszeichen. | `quotes: "“" "”";` |
| `line-break` | Bestimmt, wie Zeilenumbrüche behandelt werden. | `line-break: normal;` |
| `overflow-wrap` | Bestimmt, ob der Text umgebrochen wird, wenn er den Container überläuft. | `overflow-wrap: break-word;` |
| `word-wrap` | Bestimmt, ob der Text umgebrochen wird, wenn er den Container überläuft. | `word-wrap: break-word;` |

<style>
    html { font-size: 14px; }
    h1 { font-size: 1.2em; text-align: center; }
    table, td, th { border: 2px solid black; border-collapse: collapse; }

    @media print {
        html { font-size: 14px; }
        h1 { font-size: 1.2em; text-align: center; }
        table, td, th { border: 2px solid black; border-collapse: collapse; }
    }
</style>