---
layout: post
title:  Consigli per gli acquisti - PILOTA
subtitle: Vorrei acquistare una bicicletta a Bologna
tags: [mercato, test]
---

## Acquistare una bicicletta a Bologna

L'idea alla base di questa serie nasce come effetto collaterale del tentativo di acquistare una bicicletta a Bologna. Essendo uno degli oggetti più rubati in città ho cercato, invano, di acquistarne una di seconda mano ad un prezzo ragionevole, arrivando a constatare quanto sia difficile, fino ad accantonare l'idea. 

La "difficoltà" non dovuta al mercato poco attivo, tutt'altro. La difficoltà principale è quella di riuscire a contattare un venditore come primo acquirente, nonostante l'articolo sia stato pubblicato solo qualche ora prima. 

Questa esperienza mi ha fatto sorgere alcune domande:
* dopo quanto tempo un articolo risulta non più disponibile?
* esiste un momento del giorno, o periodo dell'anno, migliore per cercare un articolo?
* ci sono ciclicità nei movimenti di domanda e offerta del mercato dell'usato?
* quali sono gli articoli maggiormente scambiati e come sono distribuiti sul territorio?
* è possibile determinare in anticipo il miglior prezzo d'acquisto e identificare gli annunci migliori?   

## Dalla raccolta dati ai primi analytics

Avendo definito lo scopo mi sono occupato inizialmente di raccogliere i dati su cui poter lavorare e reperire le informazioni direttamente dagli annunci trovati in rete, costruendo di un semplice tool che facesse il lavoro per me e che giornalmente controllasse gli annunci pubblicati aggiornando quelli già processati.

Il perimetro disponibile ad oggi nonostante sia molto ricco, non ci permette ancora di identificare ciclicità di medio periodo, ma è ampiamente sufficiente per identificare degli insight sul mercato che stiamo osservando.

##### PERIMETRO E DATI DISPONIBILI

Ad oggi è possibile analizzare circa 215.000 annunci pubblicati da Novembre in poi nella provincia di Bologna, da arricchire con un ulteriore set relativo al solo mercato immobiliare, ancora in via di definizione.
Possiamo distinguere principalmente quattro categorie: _immobili_, _usato_, _servizi_, _veicoli_.

![](../assets/img/CPGA_PILOTA/segmento-annunci.png)

La tabella rappresenta la distribuzione degli articoli tra le categorie, mostrando che **il 27% degli annunci pubblicati rappresentano il 98% del valore economico complessivo**, e si concentrano principalmente tra veicoli e immobili.  
Essendo mercati molto diversi tra loro saranno analizzati separatamente, dividendole in tre sezioni:

* occasioni di seconda mano (usato, veicoli);
* immobili;
* servizi.

Le statistiche viste in precedenza ci indicano chiaramente quanto il mercato da esplorare sia ricco e vivo. La prima domanda a cui proviamo a rispondere è: **quanti annunci vengono pubblicati in una settimana?**

##### TREND DI PUBBLICAZIONE DEGLI ANNUNCI

[introduci il paragrafo]

![](../assets/img/CPGA_PILOTA/daily_trend.png)

Dal grafico vediamo che settimanalmente vengono pubblicati circa XXX mila annunci, con una media di XXX mila per giorno. 

È curioso notare come il periodo natalizio abbia indotto una riduzione di circa XXX mila annunci, per poi riprendere con un incremento del XXX% rispetto alla media del periodo precedente. Questo fenomeno riconducibile all'inattività degli utenti privati e dalle interruzioni delle attività lavorative delle società.

Osservando sempre più nel dettaglio anche all'interno della giorno sono presenti dei momenti in cui è presente una concentrazione maggiore degli annunci presenti in rete. 

![](../assets/img/CPGA_PILOTA/distribuzione_oraria.png)

Questo comportamento è dovuto principalmente dal tipo di utenti presenti, ovvero le aziende e gli utenti privati. Per le azienda tra le 8 e le 16 è possibile vengono pubblicati più del 70% degli annunci totali. Osservando lo stesso fenomeno per gli utenti privati si nota che un buon numero di annunci sono disponibili dalle 10 in poi e sarà necessario aspettare le 20 per poter scorrere almeno l'80% del totale. 

![](../assets/img/CPGA_PILOTA/ripartizione_oraria_cumulata.png)

**Questa considerazione ci aiuta a individuare il momento migliore della giornata entro cui osservare gli annunci disponibili.**

Questa tipologia di utenti così ripartita ci fa pensare che alcune categorie di prodotto potrebbero essere prerogativa di una delle due categorie. Si nota infatti che **tra il 75% e 85% degli annunci di immobili e veicoli vengono pubblicati dalle aziende** che sfruttano questo canale per pubblicizzare i propri prodotti, mentre **più del 80% dei prodotti del mercato dell'usato** è scambiato tra utenti privati.

![](../assets/img/CPGA_PILOTA/distribuzione_pvt_bsn.png)

Avere due tipi di inserzionisti presenta delle ripercussioni sulle fasce di prezzo dei prodotti pubblicizzati comportando una variazione di **+40% sugli appartamenti** e **+120% sulle auto**. Questo è giustificato dai margini di vendita delle aziende, dalla migliore qualità dei prodotti venduti e dalla coerenza tra prezzo indicato e valore il di mercato.

Con queste piccole evidenze si conclude il pilota di questa serie, che verranno approfondite e analizzare nei prossimi articoli.