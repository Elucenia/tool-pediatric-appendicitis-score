<!-- ELUCENIA technical documentation · pediatric-appendicitis-score · fr · no clinical/professional/rights approval -->

# Score d’appendicite pédiatrique (PAS)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/pediatric-appendicitis-score)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Douleur de la fosse iliaque droite à la toux, à la percussion ou au saut

`tosse`

### Douleur à la palpation de la fosse iliaque droite

`fid`

### Anorexie

`anorexia`

### Fièvre (\> 38 °C)

`febre`

### Nausées ou vomissements

`nausea`

### Migration de la douleur vers la fosse iliaque droite

`migra`

### Hyperleucocytose (\> 10 000/mm³)

`leuco`

### Neutrophilie (neutrophiles \> 7 500/mm³)

`neut`

## Édition de la méthode

PAS/Samuel 2002 : 8 facteurs, 0–10 ; ni Alvarado ni pARC

## Formule documentée

2 points : douleur de fosse iliaque droite à la toux, percussion ou saut ; douleur à sa palpation. 1 point : anorexie, fièvre, nausées/vomissements, migration de douleur, hyperleucocytose et neutrophilie. Total 0 à 10.

## Limites et population

Le PAS original de Samuel (2002) a été élaboré chez des enfants de 4–15 ans. La validation de Goldman (2008) a étudié des enfants de 1–17 ans présentant une douleur abdominale depuis moins de 7 jours ; elle excluait une appendicectomie antérieure et un diagnostic d’appendicite par échographie ou tomodensitométrie déjà établi à l’arrivée. L’évaluation des symptômes subjectifs demande de la prudence chez les enfants qui ne peuvent pas encore les exprimer. Le score n’est pas pARC et ne détermine pas à lui seul le diagnostic, la sortie, l’imagerie ou la chirurgie.

## Références

- [Samuel M. Pediatric appendicitis score. J Pediatr Surg, 2002.](https://doi.org/10.1053/jpsu.2002.32893)

- [Goldman RD et al. Prospective validation of the pediatric appendicitis score. J Pediatr, 2008.](https://doi.org/10.1016/j.jpeds.2008.01.033)

- [Samuel2002;DOI10.1053/jpsu.2002.32893](https://pubmed.ncbi.nlm.nih.gov/12037754/)

- [Goldman2008;DOI10.1016/j.jpeds.2008.01.033](https://emergency.med.ufl.edu/files/2013/02/prospective-validation-of-pediatric-appendicitis-score.pdf)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
