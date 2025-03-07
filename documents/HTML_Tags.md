### Die wichtigsten HTML Tags

| HTML-Tag     | Beschreibung                                      | Anwendungsbeispiel                        |
|--------------|---------------------------------------------------|-------------------------------------------|
| **Dokumenten-Struktur Tags** | | |
| `<html>`     | Wurzelelement eines HTML-Dokuments.               | `<html>...</html>`                        |
| `<head>`     | Enthält Metadaten und Verweise auf externe Ressourcen. | `<head>...</head>`                        |
| `<body>`     | Enthält den Inhalt des HTML-Dokuments.            | `<body>...</body>`                        |
| **Head Tags** | | |
| `<title>`    | Definiert den Titel des Dokuments.                | `<title>Meine Webseite</title>`           |
| `<meta />`   | Definiert Metadaten über das Dokument.            | `<meta charset="UTF-8" />`                |
| `<link />`   | Verbindet das Dokument mit einer externen Ressource. | `<link rel="stylesheet" href="styles.css" />`|
| `<style>`    | Enthält CSS-Styles für das Dokument.              | `<style>body { font-family: Arial; }</style>` |
| `<script>`   | Enthält oder verlinkt JavaScript-Code.            | `<script src="script.js"></script>`       |
| **Content Tags** | | |
| `<header>`   | Definiert den Kopfbereich eines Dokuments oder Abschnitts. | `<header>...</header>`                    |
| `<nav>`      | Definiert eine Navigationsleiste.                 | `<nav>...</nav>`                          |
| `<main>`     | Definiert den Hauptinhalt des Dokuments.          | `<main>...</main>`                        |
| `<section>`  | Definiert einen Abschnitt im Dokument.            | `<section>...</section>`                  |
| `<article>`  | Definiert einen eigenständigen Artikel.           | `<article>...</article>`                  |
| `<aside>`    | Definiert Inhalte, die indirekt mit dem Hauptinhalt zusammenhängen. | `<aside>...</aside>`                      |
| `<footer>`   | Definiert den Fußbereich eines Dokuments oder Abschnitts. | `<footer>...</footer>`                    |
| `<h1>` bis `<h6>` | Definieren Überschriften, `<h1>` ist die wichtigste. | `<h1>Überschrift 1</h1>`                  |
| `<p>`        | Definiert einen Absatz.                           | `<p>Dies ist ein Absatz.</p>`             |
| `<a>`        | Definiert einen Hyperlink.                        | `<a href="https://www.example.com">Link</a>` |
| `<img />`    | Betten ein Bild ein.                              | `<img src="bild.jpg" alt="Beschreibung" />` |
| `<br />`     | Fügt einen Zeilenumbruch ein.                     | `<br />`                                  |
| `<hr />`     | Fügt eine horizontale Linie ein.                  | `<hr />`                                  |
| `<strong>`   | Markiert wichtigen Text.                          | `<strong>Wichtiger Text</strong>`         |
| `<em>`       | Markiert betonten Text.                           | `<em>Betonter Text</em>`                  |
| `<blockquote>` | Definiert einen Blockzitat.                     | `<blockquote>Zitat</blockquote>`          |
| `<code>`     | Definiert einen Codeabschnitt.                    | `<code>console.log('Hello');</code>`      |
| **Tags mit Subtags** | | |
| `<ul>`       | Definiert eine ungeordnete Liste.                 | `<ul><li>Listenelement</li></ul>`         |
| `<ol>`       | Definiert eine geordnete Liste.                   | `<ol><li>Listenelement</li></ol>`         |
| `<li>`       | Definiert ein Listenelement.                      | `<ul><li>Listenelement</li></ul>`         |
| `<table>`    | Definiert eine Tabelle.                           | `<table><tr><th>Kopfzelle</th></tr><tr><td>Zelleninhalt</td></tr></table>` |
| `<tr>`       | Definiert eine Tabellenzeile.                     | `<table><tr><td>Zelleninhalt</td></tr></table>` |
| `<td>`       | Definiert eine Tabellenzelle.                     | `<table><tr><td>Zelleninhalt</td></tr></table>` |
| `<th>`       | Definiert eine Tabellenkopfzelle.                 | `<table><tr><th>Kopfzelle</th></tr></table>` |
| `<form>`     | Definiert ein Formular zur Benutzereingabe.       | `<form><input type="text" name="name" /></form>` |
| `<input />`  | Definiert ein Eingabefeld.                        | `<input type="text" name="name" />`       |
| `<button>`   | Definiert einen Button.                           | `<button>Click me</button>`               |
| `<label>`    | Verknüpft ein Label mit einem Eingabefeld.        | `<label for="name">Name:</label><input type="text" id="name" />` |
| `<textarea>` | Definiert ein mehrzeiliges Texteingabefeld.       | `<textarea>Text hier...</textarea>`       |
| `<select>`   | Definiert ein Dropdown-Auswahlfeld.               | `<select><option>Option 1</option></select>` |
| `<option>`   | Definiert eine Option in einem Dropdown-Auswahlfeld. | `<select><option>Option 1</option></select>` |
| `<div>`      | Definiert einen Container für Block-Elemente.     | `<div>Inhalt</div>`                       |
| `<span>`     | Definiert einen Container für Inline-Elemente.    | `<span>Inhalt</span>`                     |

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