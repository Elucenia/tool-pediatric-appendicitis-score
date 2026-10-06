<!-- ELUCENIA technical documentation · pediatric-appendicitis-score · en · no clinical/professional/rights approval -->

# Pediatric Appendicitis Score (PAS)

[conditions, sources and permissions](https://elucenia.org/en/tools/pediatric-appendicitis-score)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Right iliac fossa pain with coughing, percussion or hopping

`tosse`

### Right iliac fossa tenderness

`fid`

### Anorexia

`anorexia`

### Fever (\> 38 °C)

`febre`

### Nausea or vomiting

`nausea`

### Pain migration to the right iliac fossa

`migra`

### Leukocytosis (\> 10,000/mm³)

`leuco`

### Neutrophilia (neutrophils \> 7,500/mm³)

`neut`

## Method edition

PAS/Samuel 2002: 8 factors, 0–10; not Alvarado or pARC

## Documented formula

2 points: right lower quadrant pain with coughing, percussion or hopping; right lower quadrant tenderness. 1 point: anorexia, fever, nausea/vomiting, pain migration, leukocytosis and neutrophilia. Total 0 to 10.

## Limits and population

Samuel’s original PAS (2002) was derived in children aged 4–15 years. Goldman’s validation (2008) studied children aged 1–17 years with abdominal pain lasting less than 7 days; it excluded prior appendectomy and a diagnosis of appendicitis by ultrasound or CT already established on arrival. Assessing subjective symptoms requires care in children who cannot yet communicate them. The score is not pARC and does not determine diagnosis, discharge, imaging or surgery on its own.

## References

- [Samuel M. Pediatric appendicitis score. J Pediatr Surg, 2002.](https://doi.org/10.1053/jpsu.2002.32893)

- [Goldman RD et al. Prospective validation of the pediatric appendicitis score. J Pediatr, 2008.](https://doi.org/10.1016/j.jpeds.2008.01.033)

- [Samuel2002;DOI10.1053/jpsu.2002.32893](https://pubmed.ncbi.nlm.nih.gov/12037754/)

- [Goldman2008;DOI10.1016/j.jpeds.2008.01.033](https://emergency.med.ufl.edu/files/2013/02/prospective-validation-of-pediatric-appendicitis-score.pdf)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Low probability of appendicitis (≤ 2)

In the Goldman validation (2008), only 2.4% of children with appendicitis had PAS ≤ 2: discharge with return precautions.


### 2

Intermediate probability (3 to 6)

Investigate: observation with serial reassessment and ultrasonography (CT if ultrasonography is inconclusive).


### 3

High probability of appendicitis (≥ 7)

Pediatric surgeon assessment; in validation, only 4% of operated patients with PAS ≥ 7 did not have appendicitis.


### 4

High probability of appendicitis (≥ 7)

Pediatric surgeon assessment; in validation, only 4% of operated patients with PAS ≥ 7 did not have appendicitis.

