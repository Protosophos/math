# Q_PHI_DUALITY_CHECK.md

# Formale Pruefung des Dualpaars Ladung und Fluss

## Ziel

Geprueft wird nicht nur, ob bekannte Formeln existieren, sondern ob `Ladung` und `Fluss` tatsaechlich als spiegelbares Bestandsduo tragfaehig sind.

## Grunddaten

Standardphysikalisch:

- `Q` in Coulomb
- `I = dQ/dt`
- `Phi` in Weber
- `U = dPhi/dt` auf der Induktionsseite
- Leistung `P = U I`

## Formale Parallelitaet

Die einfachste strukturale Parallelitaet lautet:

| Seite | Bestand | Zeitableitung | Leistungsbeitrag |
| --- | --- | --- | --- |
| elektrisch | `Q` | `I` | `U I` |
| magnetisch / dual | `Phi` | `U` | `U I` |

Damit entsteht eine saubere Kreuzkopplung:

- `Q` produziert in Zeitrichtung `I`
- `Phi` produziert in Zeitrichtung `U`
- die Energieumsatzform koppelt beide Operatorausgaenge

## Dimensionspruefung

Mit `Wb = V s` gilt:

- `dPhi/dt` hat die Einheit `V`
- `dQ/dt` hat die Einheit `A`
- Produkt `V A` ist `W`

Das ist dimensionsmaessig sauber.

## Energiestruktur

Im konzentrierten Modell eines LC-Systems gilt:

- `E_C = Q^2 / (2 C)`
- `E_L = Phi^2 / (2 L)`

Das ist fuer die interne Ordnung besonders stark, weil beide Bestandsgroessen je eine quadratische Energiespeicherung tragen.

Struktureller Gewinn:

- `Q` und `Phi` sind nicht nur formal dual, sondern auch energetisch parallel speicherbar.

## Wo die Dualitaet traegt

- im LC-System sehr gut
- in konzentrierten elektrischen Netzwerken gut
- in Hamiltonschen Formulierungen gut

## Wo sie unscharf wird

- im allgemeinen Feldbild ohne konzentrierte Parameter
- sobald Spannung als global eindeutig definierte Groesse problematisch wird
- sobald `Fluss` topologisch oder flaechenspezifisch statt lokal gelesen werden muss

## Expliziter Befund

### Intern tragfaehig

- `Q` und `Phi` koennen als Bestandsduo gelesen werden.
- ihre Zeitableitungen ergeben ein operatorisches Duo `I` und `U`.
- die Energieform stuetzt die Parallelitaet stark.

### Dimensionsmaessig korrekt

- ja, in der oben genannten Form.

### Standardphysikalisch etabliert

- teilweise.
- die Einzelrelationen sind etabliert.
- die volle Lesart als primaeres Bestandsduo ist eher eine strukturierende Neuordnung als Standarddarstellung.

## Offene Arbeitsstelle

Die eigentliche Restfrage ist nicht mehr, ob das Paar formal moeglich ist, sondern:

- ob `Q ↔ Phi` nur fuer konzentrierte Systeme tragend ist
- oder ob daraus eine allgemeinere Feldordnung ableitbar ist
