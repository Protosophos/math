# S1_MECHANICAL_TEST.md

# Testbeispiel fuer S^1

## Wahl des Minimalbeispiels

Als erstes Testsystem wird die geradlinige Bewegung eines Massenpunkts mit konstanter Kraft verwendet.

Warum dieses Beispiel:

- mechanisch elementar
- Impuls, Energie und Leistung treten gleichzeitig auf
- keine zusaetzliche Schwingungs- oder Feldstruktur verdeckt die Ordnung

## System

- Masse `m`
- Ort `x(t)`
- Geschwindigkeit `v(t)`
- konstante Kraft `F`

Standardphysikalisch gilt:

- `m a = F`
- `v(t) = v_0 + a t`
- `x(t) = x_0 + v_0 t + (1/2) a t^2`
- `p = m v`
- `E_kin = (1/2) m v^2`
- `P = F v`

## Strukturtest

### 1. Zeitseite

Unter konstanter Kraft waechst der Impuls linear:

- `dp/dt = F`

Der Impuls ist hier also klar kein Endzustand, sondern das Resultat eines laufenden Uebergangs.
Das stuetzt die interne Lesart:

- `Impuls` ist prozessnah
- nicht notwendig die letzte Ruheachse

### 2. Raum-Zeit-Kopplung

Die Leistung lautet:

- `P = F v`

Hier wird sichtbar:

- Kraft allein ist noch keine Leistung
- Geschwindigkeit allein ist noch keine Leistung
- Leistung entsteht aus der Kopplung von raumgerichteter Wirkung und zeitlichem Vollzug

Innerhalb der internen Ordnung spricht das fuer:

- `Leistung` ist die explizit zeitgebundene Bestandsseite
- sie zeigt den aktuellen Energiedurchsatz

### 3. Energie als Zwischenform

Es gilt:

- `dE_kin/dt = P`

Energie ist in diesem Beispiel weder rein raumgebundener noch rein zeitgebundener Bestand.
Sie ist die integrierbare Bilanzgroesse, die aus dem Leistungsdurchsatz hervorgeht.

Das stuetzt fuer `S^1` die Lesart:

- `Energie` ist eher Mittel- oder Bilanzform
- nicht die primaere Gegenachse zu `Impuls`

### 4. Stelle des Moments

Das Beispiel zeigt etwas Wichtiges:

- `Impuls`, `Energie`, `Leistung` sind unmittelbar testbar.
- `Moment` ist hier noch nicht automatisch sichtbar.

Damit entsteht eine reale Arbeitsstelle:

- Entweder ist `Moment` in `S^1` allgemeiner als im linearen Beispiel sichtbar und braucht eine raeumliche Hebel- oder Ortsbindung.
- Oder der Begriff `Moment` ist fuer die lineare Grundordnung zu weit bzw. falsch benannt.

Diese Spannung darf nicht uebergangen werden.

## Vorlaeufiges Ergebnis

Das Beispiel bestaetigt:

- `Impuls` ist gut als Uebergangsform lesbar.
- `Leistung` hat eine stabile Zeitseitenrolle.
- `Energie` ist plausibel als Bilanz- und Integrationsgroesse.

Das Beispiel bestaetigt nicht automatisch:

- dass `Moment` bereits im einfachsten linearen S^1-Test die richtige Raum-Bestandsbezeichnung ist.

## Konsequenz

Fuer die weitere Ordnungsarbeit gibt es zwei konkurrierende Lesarten:

### Lesart A

`Moment` bleibt zentrale Raumachse.
Dann muss gezeigt werden, wie die lineare Mechanik diese Achse enthaelt oder degeneriert.

### Lesart B

`Moment` ist nur fuer eine raumgebundene Unterklasse der Mechanik zentral, nicht fuer jede S^1-Grundform.

Zur Zeit ist keine der beiden Lesarten entschieden.

## Offene Fragen aus dem Beispiel

- Ist `Moment` ohne Hebelarm oder Ortsbindung ueberhaupt sauber definiert?
- Ist fuer den linearen Fall eine andere Raum-Bestandsgroesse geeigneter?
- Ist `S^1` bereits zu breit gefasst, wenn lineare und rotatorische Strukturen ungegliedert zusammenfallen?
