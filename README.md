 Bauaktivitäten Belgien — ARDL-Modellierung & Regressionsanalyse

**Kurs:** Angewandte Ökonometrie | TH Brandenburg  
**Autor:** Yevgeniy Gubov

## Projektübersicht

Ökonometrische Modellierung der Bauaktivitäten in Belgien (2000–2023) mittels ARDL-Modell. Untersucht wird, wie Hauspreise, Einkommen, Zinssätze und Arbeitslosigkeit die Baugenehmigungen beeinflussen.

## Variablen

| Variable | Beschreibung |
|----------|--------------|
| `permits` | Baugenehmigungen (Index 2021=100) |
| `houseprice` | Hauspreisindex |
| `income` | Haushaltseinkommen |
| `unemployment` | Arbeitslosenquote (%) |
| `interest` | Zinssatz für Wohnungsbaukredite (%) |

## Methodik

- ARDL-Modellierung mit dynamischen Multiplikatoren
- Zeitreihenanalyse (2000–2023)
- Korrelationsanalyse zwischen Einflussfaktoren
- ACF-Analyse der Residuen zur Modellgüteprüfung
- Multiple Regressionsanalyse

## Tool

**Gretl** mit `DynMultCalc.gfn` Extension für dynamische Multiplikatorberechnung

## Schlüsselkonzepte

`ARDL` · `Dynamische Multiplikatoren` · `Zeitreihenanalyse` · `Belgischer Wohnungsmarkt` · `Ökonometrie`
