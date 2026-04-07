# LOG_INTEGRATION_CHAIN.md

# Logarithmische Integrationskette aus 1/x

## Funktion des Beispiels

Dieses Beispiel ist keine Nebenrechnung, sondern ein Test fuer die Hyperbelspalte:

- Start mit einer kehrwertartigen Struktur
- wiederholte Integration
- Beobachtung, wie aus Singularitaet Form wird

## Kette

Ausgangspunkt:

- `f_0(x) = 1/x`

Erste Integration:

- `f_1(x) = ln(x)`

Zweite Integration:

- `f_2(x) = x ln(x) - x`

Dritte Integration:

- `f_3(x) = (x^2 / 2) ln(x) - (3/4) x^2`

## Interne Lesart

Die Kette zeigt eine Ordnungsverschiebung:

1. `1/x` ist reine Verhaeltnis- oder Kehrwertform.
2. `ln(x)` behaelt die Singularitaet am Rand `x -> 0+`, aber entzieht sie der reinen Algebra.
3. `x ln(x) - x` wird im Ursprung beruhigt.
4. weitere Integration erzeugt glattere Formfunktionen mit markanten Punkten.

## Ableitungsprobe

- `d/dx ln(x) = 1/x`
- `d/dx [x ln(x) - x] = ln(x)`
- `d/dx [(x^2 / 2) ln(x) - (3/4) x^2] = x ln(x) - x`

Die Kette ist also formal korrekt.

## Markante Punkte

### Punkt `x = 1`

- `ln(1) = 0`
- `f_2(1) = -1`
- `f_3(1) = -3/4`

`x = 1` ist die Stelle, an der die Logarithmuskomponente ihr Vorzeichen wechselt.
Strukturell ist das ein Neutralpunkt zwischen Wachstum und Kehrwertpraegung.

### Punkt `x = e`

Da `ln(e) = 1`, entstehen vereinfachte Werte:

- `f_1(e) = 1`
- `f_2(e) = 0`
- `f_3(e) = -e^2 / 4`

Besonders auffaellig ist:

- `f_2'(x) = ln(x)`, also hat `f_2` bei `x = 1` ein Extremum
- `f_3'(x) = f_2(x)`, also hat `f_3` bei `x = e` ein Extremum

Damit wandern die charakteristischen Punkte entlang der Integrationsleiter.

## Struktureller Gewinn

Die Kette zeigt:

- Hyperbelartige Startformen bleiben nicht einfach hyperbelartig.
- Integration erzeugt neue Formtraeger.
- singulaere Operatorurspruenge koennen in spaeteren Stufen regularisierte Formen erzeugen.

Das ist fuer den Ordnungsraum wichtig, weil es die Hyperbelspalte von einer blossen Sammlung von Kehrwerten in eine eigentliche Integrationsfamilie verwandelt.

## Explizite Spannung

Die Begriffe `Hyperbelspalte` und `Logarithmuskette` sind hier heuristisch nuetzlich.
Sie sind aber noch keine abgeschlossene Klassifikation aller kehrwertartigen Operatorfamilien.

## Offene Arbeitsstellen

- allgemeine Formel fuer die n-fache Integration von `1/x` aufschreiben
- Bezug zur Raumoperatorik expliziter herstellen
- pruefen, welche Exponentenraeume denselben Typ von Punktwanderung zeigen
