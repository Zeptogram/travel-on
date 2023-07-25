# Descrizione Contratti - Pre Appello
## Contratto EsportaDati
Operazione: EsportaDati(formato: String, dati:String)

Riferimenti caso d'uso: EsportaDati

Precondizioni: L'amministratore si è autenticato nel sistema

Postcondizioni:
- Vengono correttamente esportati i dati selezionati dall'amministratore nel formato richiesto

## Contratto GeneraGrafico
Operazione: GeneraGrafico(filtroDati: String)

Riferimenti caso d'uso: Genera Grafico

Precondizioni: L'Amministratore si è autenticato nel Sistema

Postcondizioni:
- Viene generato il grafico richiesto
- Il grafico è visualizzabile dalla Web GUI

## Contratto VisualizzaStoricoPrenotazioni
Operazione: VisualizzaStoricoPrenotazioni()

Riferimenti caso d'uso: Visualizza Storico Prenotazioni

Precondizioni: L'amministratore si è autenticato nel Sistema

Postcondizioni:
- Viene visualizzato lo storico delle prenotazioni attraverso la Web GUI

