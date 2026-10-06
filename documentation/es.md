<!-- ELUCENIA technical documentation · pediatric-appendicitis-score · es · no clinical/professional/rights approval -->

# Puntuación de apendicitis pediátrica (PAS)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/pediatric-appendicitis-score)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Dolor en la fosa ilíaca derecha al toser, percutir o saltar

`tosse`

### Dolor a la palpación de la fosa ilíaca derecha

`fid`

### Anorexia

`anorexia`

### Fiebre (\> 38 °C)

`febre`

### Náuseas o vómitos

`nausea`

### Migración del dolor a la fosa ilíaca derecha

`migra`

### Leucocitosis (\> 10.000/mm³)

`leuco`

### Neutrofilia (neutrófilos \> 7.500/mm³)

`neut`

## Edición del método

PAS/Samuel 2002: 8 factores, 0–10; no Alvarado ni pARC

## Fórmula documentada

2 puntos: dolor en fosa ilíaca derecha con tos, percusión o salto; dolor a la palpación de esa fosa. 1 punto: anorexia, fiebre, náuseas/vómitos, migración del dolor, leucocitosis y neutrofilia. Total 0 a 10.

## Límites y población

El PAS original de Samuel (2002) se derivó en niños de 4–15 años. La validación de Goldman (2008) estudió a niños de 1–17 años con dolor abdominal de menos de 7 días de duración; excluyó apendicectomía previa y diagnóstico de apendicitis por ecografía o tomografía ya establecido a la llegada. La evaluación de síntomas subjetivos exige cautela en niños que aún no pueden comunicarlos. La puntuación no es pARC ni determina por sí sola diagnóstico, alta, pruebas de imagen o cirugía.

## Referencias

- [Samuel M. Pediatric appendicitis score. J Pediatr Surg, 2002.](https://doi.org/10.1053/jpsu.2002.32893)

- [Goldman RD et al. Prospective validation of the pediatric appendicitis score. J Pediatr, 2008.](https://doi.org/10.1016/j.jpeds.2008.01.033)

- [Samuel2002;DOI10.1053/jpsu.2002.32893](https://pubmed.ncbi.nlm.nih.gov/12037754/)

- [Goldman2008;DOI10.1016/j.jpeds.2008.01.033](https://emergency.med.ufl.edu/files/2013/02/prospective-validation-of-pediatric-appendicitis-score.pdf)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Baja probabilidad de apendicitis (≤ 2)

En la validación de Goldman (2008), solo el 2,4% de los niños con apendicitis tenía PAS ≤ 2: alta con indicaciones de retorno.


### 2

Probabilidad intermedia (3 a 6)

Investigar: observación con reevaluación seriada y ecografía (tomografía si la ecografía es inconclusa).


### 3

Alta probabilidad de apendicitis (≥ 7)

Evaluación del cirujano pediátrico; en la validación, solo el 4% de los operados con PAS ≥ 7 no tenían apendicitis.


### 4

Alta probabilidad de apendicitis (≥ 7)

Evaluación del cirujano pediátrico; en la validación, solo el 4% de los operados con PAS ≥ 7 no tenían apendicitis.

