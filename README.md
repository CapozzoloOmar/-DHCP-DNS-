# DHCP-DNS

L'esercizio assegnato consisteva nell'implementare una rete su Filius, suddivisa in 4 sottoreti, con ogni sottorete contenente un server DHCP e solo una rete contenente un server DNS. Inoltre, sulla stessa rete del server DNS, doveva essere presente un server HTTP in grado di esporre le proprie pagine web con il dominio "SIRulez.it".

Per implementare l'esercizio, ho seguito i seguenti passaggi:

Ho aperto Filius e ho creato una nuova topologia di rete vuota.

Ho aggiunto 4 sottoreti alla topologia.

Per ogni sottorete, ho assegnato un indirizzo IP privato utilizzando il menu contestuale della sottorete stessa.

Ho aggiunto un server DHCP a ciascuna sottorete.

Per il server DNS, ho selezionato una delle sottoreti e ho aggiunto il server DNS utilizzando l'icona "server DNS" nella barra degli strumenti.

Ho configurato le impostazioni del server DNS, impostando l'indirizzo IP del server DHCP corrispondente alla stessa sottorete.

Infine, ho aggiunto un server HTTP alla stessa sottorete del server DNS e ho configurato il server HTTP per esporre le proprie pagine web con il dominio "SIRulez.it".

In questo modo, ho creato una rete su Filius con 4 sottoreti, ogni sottorete contenente un server DHCP, una sottorete contenente un server DNS e un server HTTP che espone le pagine web con il dominio "SIRulez.it".
