<!-- ELUCENIA technical documentation · pediatric-appendicitis-score · pt-BR · no clinical/professional/rights approval -->

# Pediatric Appendicitis Score (PAS)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/pediatric-appendicitis-score)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Dor na fossa ilíaca direita à tosse, percussão ou salto

`tosse`

### Dor à palpação da fossa ilíaca direita

`fid`

### Anorexia

`anorexia`

### Febre (\> 38 °C)

`febre`

### Náuseas ou vômitos

`nausea`

### Migração da dor para a fossa ilíaca direita

`migra`

### Leucocitose (\> 10.000/mm³)

`leuco`

### Neutrofilia (neutrófilos \> 7.500/mm³)

`neut`

## Edição do método

PAS/Samuel 2002:8 fatores,0–10; sem Alvarado oup ARC

## Fórmula documentada

2 pontos: dor à tosse, percussão ou salto na fossa ilíaca direita; dor à palpação da fossa ilíaca direita. 1 ponto: anorexia, febre, náuseas/vômitos, migração da dor, leucocitose e neutrofilia. Total de 0 a 10.

## Limites e população

O PAS original de Samuel (2002) foi derivado em crianças de 4–15 anos. A validação de Goldman (2008) estudou crianças de 1–17 anos com dor abdominal há menos de 7 dias; excluiu apendicectomia prévia e diagnóstico de apendicite por ultrassonografia ou tomografia já estabelecido na chegada. A avaliação de sintomas subjetivos exige cuidado em crianças que ainda não conseguem comunicá-los. O escore não é pARC nem determina sozinho diagnóstico, alta, imagem ou cirurgia.

## Referências

- [Samuel M. Pediatric appendicitis score. J Pediatr Surg, 2002.](https://doi.org/10.1053/jpsu.2002.32893)

- [Goldman RD et al. Prospective validation of the pediatric appendicitis score. J Pediatr, 2008.](https://doi.org/10.1016/j.jpeds.2008.01.033)

- [Samuel2002;DOI10.1053/jpsu.2002.32893](https://pubmed.ncbi.nlm.nih.gov/12037754/)

- [Goldman2008;DOI10.1016/j.jpeds.2008.01.033](https://emergency.med.ufl.edu/files/2013/02/prospective-validation-of-pediatric-appendicitis-score.pdf)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
