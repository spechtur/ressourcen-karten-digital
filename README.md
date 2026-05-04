# Wie-Fragen – Ressourcen-Gespräch

Ein digitales Kartenset für Gruppen-Diskussionen zum Thema **Lernen in einer Kultur der Digitalität**.

## Worum geht es?

Dieses Tool ersetzt einen physischen Kartenstapel. Es eignet sich für Weiterbildungen, Teamgespräche oder Schulentwicklungstage, bei denen vorhandenes Wissen und Erfahrungen im Team sichtbar gemacht werden sollen – ohne Schere, Drucker oder Vorbereitung.

Eine Person öffnet die Seite auf dem Smartphone (z.B. via QR-Code), deckt Karte für Karte auf, und die Gruppe diskutiert die Fragen gemeinsam. Am Schluss steht nicht eine Liste von Namen, sondern ein Gespräch – und hoffentlich eine Ressourcenkarte, auf der steht, was jede Person ins Team einbringt.

## Funktionsweise

- 30 offene «Wie-Fragen» in 6 Kategorien: **Aufgaben · Haltung · Tools · KI · Schüler:innen · Zusammenarbeit**
- Zufällige Reihenfolge bei jedem Start
- Filterbar nach Kategorie – für gezielte Themenschwerpunkte
- «Abschliessen»-Button beendet die Runde jederzeit und zeigt eine offene Abschlussfrage
- Optimiert für Smartphone-Nutzung via QR-Code

## Einsatz

1. QR-Code zur URL generieren (z.B. über [qr-code-generator.com](https://www.qr-code-generator.com))
2. QR-Code in Miro, auf Folie oder als Ausdruck bereitstellen
3. Eine Person in der Gruppe öffnet die Seite – los geht's

Empfohlene Gruppengrösse: 8–20 Personen  
Empfohlene Zeit: 10–15 Minuten

## Anpassen

Die gesamte Anwendung besteht aus einer einzigen Datei (`index.html`). Fragen lassen sich direkt im GitHub-Editor bearbeiten – kein Buildprozess, keine Abhängigkeiten.

Um eine Frage zu ändern oder hinzuzufügen: im Array `fragen` in der Datei `index.html` die entsprechende Zeile anpassen. Jede Frage hat zwei Felder: `text` und `kat` (Kategorie).

```js
{ text: "Wie verändert sich eine Aufgabe, wenn das Endprodukt digital ist?", kat: "Aufgaben" },
```

## Lizenz

CC BY 4.0 – frei verwendbar, anpassbar und weitergebbar mit Namensnennung.

Entwickelt im Kontext der Weiterbildungsarbeit an der [Pädagogischen Hochschule Graubünden (PHGR)](https://www.phgr.ch).
