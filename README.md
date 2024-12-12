# Analisi del Dataset Los Angeles Airbnb Listing
Questo progetto riguarda l'analisi di un dataset di BnB, con vari script per filtrare e visualizzare i dati in base a diversi criteri. Qui di seguito sono descritti i diversi metodi di analisi implementati.

## Filtrare i BnB in base al range di valutazione passato
Questo script filtra i BnB in base a un intervallo di valutazione specificato dall'utente. Gli utenti possono specificare un range di valutazione minima e massima e ottenere una lista di BnB che rientrano in quel range.

## Ricerca del BnB attraverso il nome dell'host
Questo script permette agli utenti di cercare BnB utilizzando il nome dell'host. Inserendo il nome dell'host, l'utente può visualizzare informazioni dettagliate sui BnB gestiti da quell'host.

## Ricerca del BnB in base al range di prezzo
Questo script consente agli utenti di filtrare i BnB in base a un range di prezzo specificato. Gli utenti possono inserire un prezzo minimo e massimo e ottenere una lista di BnB che rientrano in quel range.

## Ricerca BnB in base al vicinato
Questo script permette di cercare i BnB in base al quartiere. Inserendo il nome del quartiere, l'utente può visualizzare informazioni sui BnB situati in quella zona.

## Ricerca i BnB prenotabili in quel momento
Questo script filtra e visualizza i BnB che sono prenotabili istantaneamente. Gli utenti possono scegliere di visualizzare i risultati in formato JSON o in formato standard.

## Grafico con il numero di BnB in base al range del prezzo da 2500 a 25000 con salto di 2500
Questo script genera un grafico a barre orizzontali che mostra il numero di BnB distribuiti in range di prezzo di 2500, da 2500 a 25000.

## Grafico con il numero di BnB in base al range del prezzo da 0 a 2000 con salto di 100
Questo script genera un grafico a barre orizzontali che mostra il numero di BnB distribuiti in range di prezzo di 100 unità, da 0 a 2000.

## Grafico con il numero dei BnB in base al quartiere
Questo script genera un grafico a barre orizzontali che mostra il numero di BnB in ciascun quartiere. Nota: il caricamento di questo grafico potrebbe richiedere un po' di tempo poiché ci sono molti quartieri.

## Grafico con il numero di BnB in base alla valutazione (due tipologie)
Il primo script genera un grafico a barre verticali che mostra il numero di BnB distribuiti in base alle valutazioni ricevute.
Il secondo mostra le medesime informazioni ma con un grafico a torta

## Mappa interattiva con Folium
Questo script crea una mappa interattiva utilizzando Folium, che rappresenta i BnB che rientrano in determinati requisiti. I BnB sono organizzati in base alla valutazione (range intero da 1 a 5). Nota: il caricamento della mappa potrebbe richiedere un po' di tempo poiché devono essere caricati fino a 1000 marker per valutazione.

# Dataset originale
Oscar Batiz, L. (2024). Dataset di analisi dei bnb di Los Angeles. Licenza: Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0). Modificato (trasformato in json).
[Link al dataset](https://www.kaggle.com/datasets/oscarbatiz/los-angeles-airbnb-listings)
