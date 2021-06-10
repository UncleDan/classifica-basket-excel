# Classifica Basket Excel

Caratteristiche:
* Classifica secondo tutti i criteri del regolamento FIBA/FIP per competizioni "round robin": 2 punti classifica per ciascuna partita vinta, 1 punto classifica per ciascuna partita persa e 0 punti classifica per le partite perse per forfait (identificate dal risultato 20-0 o 0-20); risoluzione delle parità con i criteri *Più alta differenza canestri nelle gare tra di loro*, *Più alto numero di punti gara segnati nelle gare tra di loro*, *Più alta differenza canestri in tutte le gare del gruppo*, *Più alto numero di punti gara segnati in tutte le gare del gruppo*.
* No macro e no VBA
* Ridotto uso di formule matriciali
* Sviluppato in *LibreOffice Calc* (le versioni *Microsoft Excel* sono comunque esportate da LibreOffice Calc)

Per segnalazioni o richieste di implementazione (tempo permettendo):

[https://github.com/UncleDan/classifica-basket-excel/issues](https://github.com/UncleDan/classifica-basket-excel/issues)

Le linguette rosse non sono da stampare o pubblicare.
Le linguette verdi sono da stampare o pubblicare.
Le celle non selezionabili sono protette perché descrittive o calcolate automaticamente.
Date e risultati vanno inseriti direttamente nel foglio Calendario.
La classifica si aggiorna automaticamente.

Avvertenze:
il foglio Analisi_Risultati prende i dati riga per riga dal foglio Calendario: in caso di modifica del Calendario trascinare la formula della prima riga di Analisi_Risultati per un numero di righe pari a quelle di Calendario
Bug noti:
* la formula del coefficiente potrebbe avere malfunzionamenti per valori di differenza canestri, anche multipla, superiore a 4999
* in caso di “sorteggio” delle squadre per parità di tutti i criteri, la classifica delle squadre potrebbe cambiare riaprendo il foglio perché i numeri casuali sono rigenerati ogni volta. Per risolvere il problema fissare i coefficienti incollandoli come valori
* i link alle mappe non sono cliccabili
Todo list:
* protezione celle del foglio calendario migliorabile
* valutare inserimento analisi risultati playoff

## Versione Google Sheets:
[campionato-7-squadre-7-concentramenti-solo-finali CON DATI DI ESEMPIO](https://docs.google.com/spreadsheets/d/1jukpgaSQOXN4NzxMyWj8-NbYatQ_cBrtvV-GZTBbULU/edit?usp=sharing)
