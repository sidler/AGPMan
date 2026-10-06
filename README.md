# AGPMan – Der Compliance-Held 🦸

Ein Jump'n'Run fürs Handy, direkt im Browser. Du bist **AGPMan**, der Held aus der
AGP-Software, und räumst auf: Software-Bugs, Schwachstellen, IT-Incidents,
Revisionsfeststellungen und offene Checklisten.

## Spielen

### ▶ **https://sidler.github.io/AGPMan/**

Läuft in jedem aktuellen Browser auf Handy, Tablet und Computer. Quer halten macht
am meisten Spaß.

**Als App auf dem Handy:** Seite öffnen und zum Startbildschirm hinzufügen,
dann startet AGPMan im Vollbild wie eine App.
- iPhone/iPad (Safari): *Teilen* → *Zum Home-Bildschirm*
- Android (Chrome): Menü ⋮ → *Zum Startbildschirm hinzufügen*

**Vollbild:** Der Vollbild-Knopf schaltet in Chrome, Firefox, Edge und auf Android
direkt um. Safari auf dem iPhone kann das nicht per Knopf; dort erklärt der Knopf,
wie AGPMan über „Zum Home-Bildschirm“ ganz ohne Adressleiste startet.

### Lokal spielen

Das ganze Spiel steckt in einer einzigen Datei, `index.html`, ohne weitere
Abhängigkeiten. Auch das AGP-Logo ist direkt darin eingebettet. Am Computer reicht
ein Doppelklick, und sie öffnet sich im Browser.

> **Hinweis für iPhone/iPad:** Wenn du die Datei in der Dateien-App, in Mail oder
> in einem Messenger antippst, zeigt iOS sie nur in der Schnellvorschau an. Die
> führt kein JavaScript aus, das Spiel startet dort also nicht. Nutze auf iOS
> deshalb den Link oben.

## Steuerung

| | Handy | Tastatur |
|---|---|---|
| Laufen | linke Bildschirmhälfte ◀ ▶ | ← → / A D |
| Springen | rechte Bildschirmhälfte (länger halten = höher) | Leertaste / ↑ / W |
| Haken werfen ✓ | Haken-Knopf | X / J / K |
| Pause | ⏸ oben rechts | P / Esc |
| Ton an/aus | 🔈 oben rechts | M |
| Vollbild | ⛶ oben (auf dem Startbildschirm groß beschriftet) | F |

## Gegner

| Gegner | Verhalten | Besiegen |
|---|---|---|
| 🐞 **Software-Bug** | krabbelt hin und her | Draufspringen oder 1 Haken |
| 🔓 **Schwachstelle** | fliegt in Wellen (ab Level 2) | Draufspringen oder 1 Haken |
| 🔥 **IT-Incident** | hüpft auf dich zu (ab Level 3) | Draufspringen oder 1 Haken |
| 🧐 **Revisionsfeststellung** | Prüfer mit Klemmbrett, wirft Mängelzettel (ab Level 4) | 2 Treffer |
| 📋 **Checkliste** | steht im Weg, seitlich berühren tut weh | 3 Punkte abhaken (Sprung oder Haken) |

Mängelzettel und Exploits kannst du mit einem Haken abfangen.

## Spielregeln

- Draufspringen gibt Combo-Punkte, wenn du mehrere Gegner hintereinander erwischst.
- **Gruben**: Wer reinfällt, verliert ein Leben (*Datenverlust!*).
- **Compliance-Punkt** ✓ = Punkte, **Kaffee** ☕ = Kapazität auffüllen,
  **Backup** 💾 = Extraleben (max. 5 Schilde).
- Die **Kapazität** füllt sich langsam von selbst wieder auf; jeder Haken kostet 10 %.
- Ziel jedes Levels ist das **Testat** mit Prüfsiegel. Jedes Level wird länger und schwerer.
- Alle fünf Level wechselt die Kulisse: **Büro → Rechenzentrum → Prüfungsraum → Quellcode**.
- Jedes fünfte Level ist ein **Boss-Kampf**. Erst wenn der Boss besiegt ist,
  erscheint das Testat:
  - Level 5: **Major Incident**: springt und verteilt beim Aufprall Feuerbälle.
  - Level 10: **Zero-Day**: teleportiert sich und schießt Exploits.
  - Level 15: **Der Prüfer**: drei Phasen mit Mängelzettel-Regen.
  - Danach kehren die Bosse stärker und schneller zurück.
- Der Rekord wird im Browser gespeichert.

## Veröffentlichen (GitHub Pages)

*Settings → Pages → Build and deployment*: Source **Deploy from a branch**,
Branch **main** und Ordner **/ (root)**. Danach ist das Spiel unter
`https://sidler.github.io/AGPMan/` erreichbar.
