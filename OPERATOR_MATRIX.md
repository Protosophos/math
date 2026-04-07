# OPERATOR_MATRIX.md

# Erste Matrixdarstellung der Operatorrichtungen

## Ziel

Die Matrix soll keine fertige Endform vortaeuschen.
Sie dient dazu, die Richtungen systematisch zu entflechten:

- Raumoperatorik
- Zeitoperatorik
- Bestand
- Uebergang
- Akkumulation

## Grundmatrix

| Ebene | Raumrichtung | Neutralzone | Zeitrichtung |
| --- | --- | --- | --- |
| Differentiell 2 | Raumimpuls 2 | Sprung / Zeitimpuls | Zeitimpuls 2 |
| Differentiell 1 | raumseitige Aenderung | Uebergang | zeitseitige Aenderung |
| Bestand | Raumbestand | Schnitt / lokaler Fixpunkt | Zeitbestand |
| Integral 1 | raumseitige Akkumulation | Bilanz | zeitseitige Akkumulation |
| Integral 2 | raumseitige Akkumulation 2 | Langzeitspeicher | zeitseitige Akkumulation 2 |

Diese Matrix ist zunaechst formal.
Die Felder sind noch nicht alle mit stabilen Fachgroessen besetzt.

## Vorlaeufige Besetzung fuer S^1

| Matrixrolle | Groesse | Status |
| --- | --- | --- |
| Raumbestand | Moment | offen, begrifflich unscharf |
| Schnitt / Uebergang | Impuls | intern tragend |
| Zeitbestand | Leistung | intern tragend |
| zeitseitige Akkumulation | Energie oder Wirkung | noch zu trennen |

Wichtiger Befund:

- Die Matrix zwingt dazu, `Energie` und `Wirkung` nicht unbesehen zusammenzuwerfen.

## Vorlaeufige Besetzung fuer S^2

| Matrixrolle | Groesse | Status |
| --- | --- | --- |
| eine Bestandsseite | Ladung `Q` | tragend |
| gespiegelte Bestandsseite | Fluss `Phi` | tragend |
| Zeitableitung von `Q` | Strom `I` | standardphysikalisch klar |
| Zeitableitung von `Phi` | Spannung `U` | in konzentrierter Lesart klar |

## Leseregel

Ein Begriff ist in der Matrix erst dann stabil, wenn drei Fragen beantwortet sind:

1. Ist er Bestand, Uebergang oder Akkumulation?
2. Liegt er raumseitig, zeitseitig oder gespiegelt dazwischen?
3. Bleibt die Zuordnung in Beispielen erhalten?

## Explizite Bruchstellen

- Die obere differentielle Zeile ist noch fast unbesetzt.
- Die Neutralzone mischt derzeit mehrere Typen: Schnitt, Fixpunkt, Bilanz.
- `S^1` und `S^2` benutzen dieselbe Matrixform, aber nicht zwingend dieselbe semantische Besetzung.

## Arbeitsregel

Neue Groessen sollten kuenftig erst in die Matrix eingetragen werden und erst danach als zentrale Begriffe gelten.
