# Tulpenstrasse 15, Sindelfingen, Wohnung Nr. 3

## Was in diesem Ordner liegt

    index.html          das Expose
    bilder/             22 Bilddateien, vom Expose eingebunden
    unterlagen/         11 PDF, ueber die Downloadkarten verlinkt

Alle drei muessen beieinander bleiben. Fehlt "bilder", zeigt die Seite
keine Fotos. Fehlt "unterlagen", laufen die Downloads ins Leere.

## Stand dieser Fassung

Aufgebaut auf Doros Fassung der Wohnung Nr. 2 (Wohnung_2_18.09.2026).
Struktur, Gestaltung, Rechner, Zinsstartwert und rechtliche Hinweise sind
unveraendert. Geaendert wurden die objektbezogenen Angaben der Nr. 3:

    1. Obergeschoss rechts, 63,85 m2, Balkon mit Abstellraum
    Baujahr 1987, nach Umbau
    Kaltmiete 490,68 EUR seit 01.02.2026 (Mieterhoehung vom 04.09.2025),
    Stellplatz 60 EUR, Mieter seit 1995
    Marktmiete nach Renovierung 894 EUR (14,00 EUR/m2 wie die renovierte Nr. 4)
    Kaufpreis je m2 2.850 EUR ohne Stellplatz
    Mietsubvention 6.380 EUR: Januar 2027 bis Januar 2029 je 140 EUR
    (25 Monate), Februar 2029 bis Januar 2032 je 80 EUR (36 Monate),
    Auszahlung in einer Summe beim Kauf
    Gebaeudeanteil 74,46 Prozent, abgeleitet aus dem Wert der Nr. 2
    Eigene Fotos und Grundriss der Nr. 3
    Renovierungsbilder zeigen die Nr. 4 auf demselben Geschoss
    Ansprechpartnerin Anna Dogic

## Bitte pruefen

Die Herleitung der Kaufpreisaufteilung Nr. 3 nennt vertraglich 55,35
Prozent Gebaeudeanteil (bei Nr. 2 ebenso 55,11 Prozent laut Herleitung).
Das Exposé-Briefing WE 3 nennt noch 7.920 EUR Mietsubvention und
ca. 17.600 EUR Renovierungskosten. Im Exposé stehen wie bei Nr. 2
rund 15.000 EUR nach dem vorliegenden Angebot.
EXPOSE_URL im Skript: https://wuerttembergerwohnkonzepte.github.io/TS15-Wohnung_3/

## Hochladen

Ein eigenes Repository fuer diese Wohnung anlegen. Dann auf
"Add file", danach "Upload files", und in das Fenster alles drei
zusammen ziehen:

    index.html
    bilder            (der ganze Ordner)
    unterlagen        (der ganze Ordner)

Wichtig: nicht den Ordner "Wohnung-3" hochladen, sondern seinen Inhalt.
Die index.html muss im Repository ganz oben liegen.

## Pages einschalten

Settings, dann Pages. Bei Source "Deploy from a branch" waehlen,
Branch `main`, Ordner `/ (root)`. Speichern. Der erste Aufbau dauert
ein bis zwei Minuten, danach steht die Adresse oben auf der Seite.

## Groessen

Keine Datei ist groesser als rund 3,6 MB. Der Weblader von GitHub nimmt
einzelne Dateien bis 25 MB, das ist also unproblematisch.
Die Seite selbst laedt beim Besucher mit rund 2,8 MB, davon 2,65 MB Bilder,
die nach dem Text nachgeladen werden.

## Nicht enthalten, mit Absicht

Das Restnutzungsdauergutachten liegt nicht in "unterlagen". Es enthaelt
personenbezogene Daten. Auf GitHub Pages ist jede Datei im Repository
oeffentlich abrufbar, auch wenn sie auf der Seite nicht verlinkt ist.
Im Expose steht deshalb, dass Grundbuchauszug, Restnutzungsdauergutachten
und Mietvertrag bei ernsthaftem Kaufinteresse nachgereicht werden.
Dasselbe gilt fuer den Mietvertrag und den Grundbuchauszug.

## Falls ein Ordner anders heissen soll

In der index.html steht im Skript genau eine Zeile:

    var DOKBASE='unterlagen/';

Nur diese aendern. Der Schraegstrich am Ende muss bleiben.
Der Bildordner ist in den Bildpfaden hinterlegt und heisst "bilder".

## Hinweis zum Oeffnen von der Festplatte

Oeffnest du die index.html per Doppelklick, sperrt der Browser bei
manchen Einstellungen den Zugriff auf Nachbarordner. Die Seite erscheint,
die Downloads funktionieren dort aber nicht immer. Auf der
veroeffentlichten Seite laeuft alles.
