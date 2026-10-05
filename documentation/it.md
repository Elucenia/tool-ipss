<!-- ELUCENIA technical documentation · ipss · it · no clinical/professional/rights approval -->

# IPSS (punteggio internazionale dei sintomi prostatici)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/ipss)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Svuotamento incompleto: sensazione di non svuotare completamente la vescica

`esvaz`

- `0` — Mai
- `1` — Meno di 1 volta su 5
- `2` — Meno della metà delle volte
- `3` — Circa la metà delle volte
- `4` — Più della metà delle volte
- `5` — Quasi sempre

### Frequenza: necessità di urinare di nuovo dopo meno di 2 ore

`freq`

- `0` — Mai
- `1` — Meno di 1 volta su 5
- `2` — Meno della metà delle volte
- `3` — Circa la metà delle volte
- `4` — Più della metà delle volte
- `5` — Quasi sempre

### Intermittenza: il flusso urinario si interrompe e riprende più volte

`inter`

- `0` — Mai
- `1` — Meno di 1 volta su 5
- `2` — Meno della metà delle volte
- `3` — Circa la metà delle volte
- `4` — Più della metà delle volte
- `5` — Quasi sempre

### Urgenza: difficoltà a trattenere l’urina

`urg`

- `0` — Mai
- `1` — Meno di 1 volta su 5
- `2` — Meno della metà delle volte
- `3` — Circa la metà delle volte
- `4` — Più della metà delle volte
- `5` — Quasi sempre

### Flusso urinario debole

`jato`

- `0` — Mai
- `1` — Meno di 1 volta su 5
- `2` — Meno della metà delle volte
- `3` — Circa la metà delle volte
- `4` — Più della metà delle volte
- `5` — Quasi sempre

### Sforzo: necessità di spingere per iniziare a urinare

`esforco`

- `0` — Mai
- `1` — Meno di 1 volta su 5
- `2` — Meno della metà delle volte
- `3` — Circa la metà delle volte
- `4` — Più della metà delle volte
- `5` — Quasi sempre

### Nicturia: quante volte si è alzato di notte per urinare

`noct`

- `0` — Nessuna
- `1` — 1 volta
- `2` — 2 volte
- `3` — 3 volte
- `4` — 4 volte
- `5` — 5 o più volte

## Edizione del metodo

AUASI/Barry 1992, IPSS 7 item 0–5, totale 0–35; qualità di vita, 8º item separato

## Formula documentata

Sette domande sull’ultimo mese, ciascuna da 0 a 5 punti. Totale 0–35.

L’8ª domanda (qualità di vita, da 0 "felicissimo" a 6 "pessimo") è registrata separatamente e non entra nella somma.

## Limiti e popolazione

L’IPSS/AUA quantifica i sintomi urinari e la loro evoluzione, ma il totale non stabilisce che la causa sia l’iperplasia prostatica benigna. La validazione originale ha coinvolto persone con IPB e controlli. Formulazione, finestra temporale, qualità della vita e limiti della versione linguistica devono essere preservati e verificati separatamente.

## Riferimenti

- [Barry MJ et al. The American Urological Association symptom index for benign prostatic hyperplasia. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)36966-5)

- [Lerner LB et al. Management of lower urinary tract symptoms attributed to benign prostatic hyperplasia: AUA guideline part I, initial work-up and medical management. J Urol, 2021.](https://doi.org/10.1097/JU.0000000000002183)

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
