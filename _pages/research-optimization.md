---
layout: archive
title: "Ottimizzazione e Metaeuristiche"
permalink: /ricerca/optimization/
author_profile: true
---

L’ottimizzazione rappresenta un ambito centrale nell’analisi di sistemi complessi, in cui l’obiettivo è individuare soluzioni efficienti in presenza di vincoli e molteplici criteri decisionali. In contesti reali, tali problemi sono spesso caratterizzati da elevata dimensionalità, non linearità e presenza di più obiettivi, rendendo difficile l’applicazione di metodi deterministici tradizionali.

In questo scenario, le metaeuristiche e gli algoritmi evolutivi costituiscono strumenti particolarmente efficaci, in quanto permettono di esplorare spazi di soluzione complessi attraverso strategie ispirate a processi naturali, come la selezione genetica o il comportamento collettivo.

## Algoritmi genetici e ottimizzazione evolutiva

Gli algoritmi genetici rappresentano una delle principali metodologie utilizzate per affrontare problemi di ottimizzazione complessi. Basati su operatori come selezione, crossover e mutazione, tali algoritmi consentono di esplorare lo spazio delle soluzioni in modo flessibile ed efficace, adattandosi a contesti in cui le relazioni tra variabili non sono esplicitamente note.

In questo ambito, sono stati sviluppati modelli evolutivi avanzati per problemi di ottimizzazione multi-obiettivo.

<p align="center">
  <img src="/images/evofolio.png" width="500">
</p>

<p align="center" style="font-size: 0.9em; color: #666;">
Guarino, A., Santoro, D., Grilli, L., Zaccagnino, R., & Balbi, M. (2024). 
<i>EvoFolio: a portfolio optimization method based on multi-objective evolutionary algorithms</i>, Neural Computing & Applications.
</p>

L’uso di questi strumenti permette di integrare dinamicamente informazioni e vincoli, migliorando l’efficienza della ricerca di soluzioni ottimali rispetto ai metodi tradizionali.

## Metaeuristiche e problemi su grafi

n’altra area rilevante riguarda l’applicazione di metaeuristiche a problemi su grafi e reti, che emergono frequentemente in contesti logistici, infrastrutturali e territoriali. In tali scenari, la complessità combinatoria e la presenza di vincoli strutturali rendono spesso impraticabile l’utilizzo di metodi esatti, rendendo necessarie tecniche di ottimizzazione approssimata.

Tra queste, l’**Ant Colony Optimization (ACO)** rappresenta un approccio particolarmente efficace, ispirato al comportamento collettivo delle colonie di formiche. L’idea alla base del metodo consiste nella simulazione di agenti che esplorano lo spazio delle soluzioni depositando e seguendo tracce di feromone, permettendo una progressiva convergenza verso percorsi ottimali.

Nel contesto dei problemi su grafi, tali algoritmi risultano particolarmente adatti per la risoluzione di varianti del **Chinese Postman Problem**, in cui è necessario individuare percorsi minimi che attraversino tutti gli archi di una rete. L’estensione di questi metodi a dati reali introduce ulteriori complessità, legate alla struttura irregolare delle reti e alla presenza di vincoli operativi.

<p align="center">
  <img src="/images/aco.png" width="500">
</p>

<p align="center" style="font-size: 0.9em; color: #666;">
Rappresentazione grafica dello ski resort (Madonna di Campiglio) e modello di mappa come un grafo "directed". Sgarro, G. A., Santoro, D., & Grilli, L. (2024). 
<i>Ant Colony Optimization for solving Directed Chinese Postman Problem</i>, Neural Computing & Applications.
</p>

L’applicazione di questi modelli a dati aperti e contesti reali ha permesso di estendere le formulazioni teoriche a scenari più complessi, introducendo varianti del problema in cui la rete presenta caratteristiche non standard, come archi misti, direzionalità parziale e incompletezza delle informazioni.

Una particolare applicazione riguarda l’analisi della rete stradale dei **Monti Dauni**, un’area caratterizzata da una morfologia complessa e da una struttura infrastrutturale articolata. In questo caso, il problema è stato modellato come una variante del Chinese Postman Problem, con l’obiettivo di individuare percorsi ottimali in grado di garantire una copertura efficiente della rete.

<p align="center">
  <img src="/images/montidauni.png" width="500">
</p>

<p align="center" style="font-size: 0.9em; color: #666;">
Comune di Volturino (FG). Sgarro, G. A., Santoro, D., & Grilli, L. (2026). 
<i>Ant colony optimization for solving mixed Chinese postman problem on open real world data</i>, Neural Computing & Applications.
</p>

L’utilizzo di algoritmi ACO in questo contesto ha consentito di affrontare la complessità del problema in presenza di dati reali, evidenziando come approcci basati su intelligenza collettiva possano fornire soluzioni robuste ed efficienti anche in scenari caratterizzati da elevata variabilità e incertezza.

Nel complesso, queste applicazioni mostrano come le metaeuristiche possano rappresentare strumenti fondamentali per la gestione e l’ottimizzazione di sistemi complessi, contribuendo allo sviluppo di modelli avanzati per la pianificazione e il supporto alle decisioni in contesti reali.

## Ottimizzazione multi-obiettivo e sistemi complessi

Approcci evolutivi risultano particolarmente adatti a questo tipo di problemi, in quanto consentono di esplorare simultaneamente diverse regioni dello spazio delle soluzioni mantenendo una popolazione di alternative candidate.

In questo contesto, sono stati sviluppati modelli basati su algoritmi genetici per la costruzione di soluzioni ottimali in ambienti complessi, tra cui l’**Optimal Multivariate Mixture (OMM)**. Tali approcci permettono di combinare distribuzioni e strategie decisionali diverse, individuando configurazioni efficienti anche in presenza di elevata variabilità e incertezza.

L’utilizzo di tecniche evolutive in questo ambito consente di affrontare problemi multi-obiettivo in cui è necessario bilanciare criteri contrastanti, fornendo al decisore un insieme di soluzioni efficienti piuttosto che una singola soluzione ottimale.

<p align="center">
  <img src="/images/omm.png" width="500">
</p>

<p align="center" style="font-size: 0.9em; color: #666;">
Sgarro, G. A., Santoro, D., & Grilli, L. (2024). 
<i>Optimal multivariate mixture: a genetic algorithm approach</i>, Annals of Operations Research.
</p>
