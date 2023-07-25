# Descrizione Casi d'Uso - Pre Appello
## Esporta Dati
| SELEZIONE DEL CASO D'USO | DESCRIZIONE |
| --- | --- |
| Nome del Caso d'Uso | Esporta Dati |
| Portata | Sistema Travel On |
| Livello | Obiettivo Amministratore |
| Attore Primario | Amministratore |
| Parti Interessate e Interessi | Amministratore: vuole esportare dei dati dal sistema |
| Pre-condizioni |è presente almeno un dato nel sistema, al fine di esportare dei dati non vuoti |
| Garanzia di successo | I dati sono stati esportati con successo nel formato richiesto |
| Scenario Principale di successo | 1) Il Caso d'uso inizia con l'Amministratore che accede al sistema <br> 2) L'Amministratore seleziona l'opzione di Esportazione dati <br> 3) L'amministratore seleziona i dati da esportare  <br> 4) L'amministratore seleziona il formato in cui scaricare i dati <br>5) L'amministratore scarica i dati richiesti|
| Estensioni | __2A) Dati non presenti__<br>2A.1) Non è possibile esportare i dati senza alcun dato| 
| Requisiti speciali | Nessuno |
| Frequenza di ripetizione | Ininterrotto se sono presenti dei dati| 

## Genera Grafico
| SELEZIONE DEL CASO D'USO | DESCRIZIONE |
| --- | --- |
| Nome del Caso d'Uso | Genera Grafico |
| Portata | Sistema Travel On |
| Livello | Obiettivo Amministratore |
| Attore Primario | Amministratore |
| Parti Interessate e Interessi | Amministratore: vuole generare il grafico dello storico dei dati |
| Pre-condizioni | Sono presenti dei dati, al fine di generare un grafico non vuoto |
| Garanzia di successo | Il grafico è visibile |
| Scenario Principale di successo | 1) Il Caso d'uso inizia con l'Amministratore che accede al sistema <br> 2) L'Amministratore seleziona l'opzione di generare un grafico <br> 3) L'Amministratore filtra i dati che vuole mostrare <br> 4) Il grafico richiesto è visualizzabile dal Sistema |
| Estensioni | __3A) Non sono presenti dati__ <br> 3A.1) Non è possibile generare un grafico senza alcun dato | 
| Requisiti speciali | Nessuno |
| Frequenza di ripetizione | Ininterrotto se sono presenti di dati |


## Visualizza Storico Prenotazioni
| SELEZIONE DEL CASO D'USO | DESCRIZIONE |
| --- | --- |
| Nome del Caso d'Uso | Visualizza Storico Prenotazioni |
| Portata | Sistema Travel On |
| Livello | Obiettivo Amministratore |
| Attore Primario | Amministratore |
| Parti Interessate e Interessi | Amministratore: vuole visualizzare lo storico delle prenotazioni |
| Pre-condizioni | Almeno una prenotazione è stata effettuata, al fine di visualizzare uno storico non vuoto |
| Garanzia di successo | Lo storico è correttamente visualizzabile dall'Amministratore |
| Scenario Principale di successo | 1) Il Caso d'uso inizia con l'Amministratore che accede al Sistema <br> 2) L'Amministratore seleziona l'opzione di visualizzare lo storico delle prenotazioni <br> 3) L'Amministratore conferma l'operazione di visualizzazione dello storico  <br> 4) Lo storico delle prenotazioni è ora visualizzabile |
| Estensioni | __4A) Dati prenotazioni non presenti__ <br> 4A.1) Non è possibile visualizzare lo storico in quanto non sono presenti dati di prenotazione | 
| Requisiti speciali | Nessuno |
| Frequenza di ripetizione | Ininterrotto se sono presenti prenotazioni |
