<!-- ELUCENIA technical documentation · pediatric-appendicitis-score · it · no clinical/professional/rights approval -->

# Punteggio di appendicite pediatrica (PAS)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/pediatric-appendicitis-score)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Dolore in fossa iliaca destra con tosse, percussione o salto

`tosse`

### Dolorabilità in fossa iliaca destra

`fid`

### Anoressia

`anorexia`

### Febbre (\> 38 °C)

`febre`

### Nausea o vomito

`nausea`

### Migrazione del dolore in fossa iliaca destra

`migra`

### Leucocitosi (\> 10.000/mm³)

`leuco`

### Neutrofilia (neutrofili \> 7.500/mm³)

`neut`

## Edizione del metodo

PAS/Samuel 2002: 8 fattori, 0–10; non Alvarado o pARC

## Formula documentata

2 punti: dolore in fossa iliaca destra con tosse, percussione o salto; dolorabilità alla palpazione. 1 punto: anoressia, febbre, nausea/vomito, migrazione del dolore, leucocitosi e neutrofilia. Totale 0 a 10.

## Limiti e popolazione

Il PAS originale di Samuel (2002) è stato derivato in bambini di 4–15 anni. La validazione di Goldman (2008) ha studiato bambini di 1–17 anni con dolore addominale da meno di 7 giorni; ha escluso un’appendicectomia precedente e una diagnosi di appendicite mediante ecografia o tomografia già stabilita all’arrivo. La valutazione dei sintomi soggettivi richiede cautela nei bambini che non riescono ancora a comunicarli. Il punteggio non è pARC e non determina da solo diagnosi, dimissione, diagnostica per immagini o chirurgia.

## Riferimenti

- [Samuel M. Pediatric appendicitis score. J Pediatr Surg, 2002.](https://doi.org/10.1053/jpsu.2002.32893)

- [Goldman RD et al. Prospective validation of the pediatric appendicitis score. J Pediatr, 2008.](https://doi.org/10.1016/j.jpeds.2008.01.033)

- [Samuel2002;DOI10.1053/jpsu.2002.32893](https://pubmed.ncbi.nlm.nih.gov/12037754/)

- [Goldman2008;DOI10.1016/j.jpeds.2008.01.033](https://emergency.med.ufl.edu/files/2013/02/prospective-validation-of-pediatric-appendicitis-score.pdf)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Bassa probabilità di appendicite (≤ 2)

Nella validazione di Goldman (2008), solo il 2,4% dei bambini con appendicite aveva PAS ≤ 2: dimissione con indicazioni di ritorno.


### 2

Probabilità intermedia (3 a 6)

Indagare: osservazione con rivalutazione seriata ed ecografia (TC se l’ecografia è inconclusiva).


### 3

Alta probabilità di appendicite (≥ 7)

Valutazione del chirurgo pediatrico; nella validazione, solo il 4% degli operati con PAS ≥ 7 non aveva appendicite.


### 4

Alta probabilità di appendicite (≥ 7)

Valutazione del chirurgo pediatrico; nella validazione, solo il 4% degli operati con PAS ≥ 7 non aveva appendicite.

