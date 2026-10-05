<!-- ELUCENIA technical documentation · pediatric-appendicitis-score · de · no clinical/professional/rights approval -->

# Pädiatrischer Appendizitis-Score (PAS)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/pediatric-appendicitis-score)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Schmerz im rechten Unterbauch bei Husten, Perkussion oder Hüpfen

`tosse`

### Druckschmerz im rechten Unterbauch

`fid`

### Anorexie

`anorexia`

### Fieber (\> 38 °C)

`febre`

### Übelkeit oder Erbrechen

`nausea`

### Wanderung des Schmerzes in den rechten Unterbauch

`migra`

### Leukozytose (\> 10.000/mm³)

`leuco`

### Neutrophilie (Neutrophile \> 7.500/mm³)

`neut`

## Fassung der Methode

PAS/Samuel 2002: 8 Faktoren, 0–10; kein Alvarado oder pARC

## Dokumentierte Formel

2 Punkte: Schmerz im rechten Unterbauch bei Husten, Perkussion oder Hüpfen; Druckschmerz dort. 1 Punkt: Anorexie, Fieber, Übelkeit/Erbrechen, Schmerzwanderung, Leukozytose und Neutrophilie. Gesamt 0 bis 10.

## Grenzen und Population

Der ursprüngliche PAS von Samuel (2002) wurde bei Kindern im Alter von 4–15 Jahren entwickelt. Die Validierung von Goldman (2008) untersuchte Kinder von 1–17 Jahren mit Bauchschmerzen seit weniger als 7 Tagen; ausgeschlossen waren eine frühere Appendektomie und eine bereits bei Ankunft durch Ultraschall oder Computertomografie gesicherte Appendizitisdiagnose. Die Beurteilung subjektiver Symptome erfordert Vorsicht bei Kindern, die diese noch nicht mitteilen können. Der Score ist nicht pARC und legt Diagnose, Entlassung, Bildgebung oder Operation nicht allein fest.

## Referenzen

- [Samuel M. Pediatric appendicitis score. J Pediatr Surg, 2002.](https://doi.org/10.1053/jpsu.2002.32893)

- [Goldman RD et al. Prospective validation of the pediatric appendicitis score. J Pediatr, 2008.](https://doi.org/10.1016/j.jpeds.2008.01.033)

- [Samuel2002;DOI10.1053/jpsu.2002.32893](https://pubmed.ncbi.nlm.nih.gov/12037754/)

- [Goldman2008;DOI10.1016/j.jpeds.2008.01.033](https://emergency.med.ufl.edu/files/2013/02/prospective-validation-of-pediatric-appendicitis-score.pdf)

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
