<!-- ELUCENIA technical documentation · ipss · de · no clinical/professional/rights approval -->

# IPSS (Internationaler Prostata-Symptom-Score)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/ipss)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Unvollständige Entleerung: Gefühl, die Blase nicht vollständig entleert zu haben

`esvaz`

- `0` — Nie
- `1` — Weniger als 1 Mal von 5
- `2` — Weniger als die Hälfte der Zeit
- `3` — Etwa die Hälfte der Zeit
- `4` — Mehr als die Hälfte der Zeit
- `5` — Fast immer

### Häufigkeit: erneutes Wasserlassen weniger als 2 Stunden später erforderlich

`freq`

- `0` — Nie
- `1` — Weniger als 1 Mal von 5
- `2` — Weniger als die Hälfte der Zeit
- `3` — Etwa die Hälfte der Zeit
- `4` — Mehr als die Hälfte der Zeit
- `5` — Fast immer

### Unterbrechungen: der Harnstrahl stoppt und beginnt mehrmals wieder

`inter`

- `0` — Nie
- `1` — Weniger als 1 Mal von 5
- `2` — Weniger als die Hälfte der Zeit
- `3` — Etwa die Hälfte der Zeit
- `4` — Mehr als die Hälfte der Zeit
- `5` — Fast immer

### Harndrang: Schwierigkeiten, das Wasserlassen aufzuschieben

`urg`

- `0` — Nie
- `1` — Weniger als 1 Mal von 5
- `2` — Weniger als die Hälfte der Zeit
- `3` — Etwa die Hälfte der Zeit
- `4` — Mehr als die Hälfte der Zeit
- `5` — Fast immer

### Schwacher Harnstrahl

`jato`

- `0` — Nie
- `1` — Weniger als 1 Mal von 5
- `2` — Weniger als die Hälfte der Zeit
- `3` — Etwa die Hälfte der Zeit
- `4` — Mehr als die Hälfte der Zeit
- `5` — Fast immer

### Pressen: Kraftaufwand nötig, um mit dem Wasserlassen zu beginnen

`esforco`

- `0` — Nie
- `1` — Weniger als 1 Mal von 5
- `2` — Weniger als die Hälfte der Zeit
- `3` — Etwa die Hälfte der Zeit
- `4` — Mehr als die Hälfte der Zeit
- `5` — Fast immer

### Nykturie: wie oft Sie nachts zum Wasserlassen aufgestanden sind

`noct`

- `0` — Keine
- `1` — 1 Mal
- `2` — 2 Mal
- `3` — 3 Mal
- `4` — 4 Mal
- `5` — 5-mal oder häufiger

## Fassung der Methode

AUASI/Barry 1992, IPSS 7 Items 0–5, gesamt 0–35; Lebensqualität, 8. Item separat

## Dokumentierte Formel

Sieben Fragen zum letzten Monat, jeweils 0 bis 5 Punkte. Gesamt 0 bis 35.

Die 8. Frage (Lebensqualität, von 0 "ausgezeichnet" bis 6 "sehr schlecht") wird separat erfasst und nicht zur Summe gezählt.

## Grenzen und Population

IPSS/AUA quantifiziert Harnwegssymptome und ihren Verlauf, doch die Summe stellt keine benigne Prostatahyperplasie als Ursache fest. Die Originalvalidierung umfasste Personen mit BPH und Kontrollen. Wortlaut, Zeitfenster, Lebensqualität und Grenzen der Sprachversion müssen erhalten und getrennt geprüft werden.

## Referenzen

- [Barry MJ et al. The American Urological Association symptom index for benign prostatic hyperplasia. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)36966-5)

- [Lerner LB et al. Management of lower urinary tract symptoms attributed to benign prostatic hyperplasia: AUA guideline part I, initial work-up and medical management. J Urol, 2021.](https://doi.org/10.1097/JU.0000000000002183)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Leichte Symptome (0 bis 7)

Im Allgemeinen abwartendes Beobachten und Verhaltensempfehlungen.


### 2

Mäßige Symptome (8 bis 19)

Eine medikamentöse Behandlung je nach Beschwerdegrad erwägen.


### 3

Schwere Symptome (20 bis 35)

Kombinierte medikamentöse oder chirurgische Behandlung erwägen.

