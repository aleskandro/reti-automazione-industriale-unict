### Specifiche

*  Ogni led puó trovarsi nello stato acceso/spento

*  Solo un LED puó (e deve) essere selezionato

*  Il led selezionato lampeggia con periodo

    -  500ms (stato spento)
    -  100ms (stato acceso)

*  La pressione prolungata del tasto cambia lo stato del led selezionato (acceso <-> spento)

*  La pressione regolare (non prolungata) del tasto cambia il led selezionato con il successivo in senso orario

### Note

* Senza interrupt e' poco usabile

* Gli stati del pulsante potrebbero essere implementati come FSM per eleganza
