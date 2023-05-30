# Magazzino-Informatizzato
____________________________________
## Diagramma UML della prima funzionalita 
![Banner](https://github.com/Matteo2022/Magazzino-Informatizzato-4AII/blob/c9e0241cf564b268fc77cb4613cb940de1dae2b5/UML.png)
________________________________________
### Descrizione digramma UML della prima funzionalità
Il diagramma rappresenta le classi principali coinvolte nel processo di pianificazione e ottimizzazione degli spazi di un magazzino informatizzato utilizzando Python. La classe Magazzino informatizzato rappresenta il magazzino stesso e contiene le liste di prodotti e spazi, nonché i requisiti normativi e di sicurezza. La classe Prodotto rappresenta un prodotto del magazzino e contiene informazioni come il nome, le dimensioni e la frequenza di vendita. La classe Spazio rappresenta uno spazio di stoccaggio del magazzino e contiene informazioni come l'ID, le dimensioni e la posizione.

La classe PyomoModel rappresenta il modello di programmazione lineare utilizzato per la pianificazione della disposizione dei prodotti all'interno del magazzino. Contiene le liste di prodotti e spazi, nonché i requisiti normativi e di sicurezza, e utilizza la libreria Pyomo per definire e risolvere il modello.

Infine, la classe MatplotlibPlot rappresenta lo strumento di visualizzazione dei dati utilizzato per visualizzare la disposizione dei prodotti all'interno del magazzino e identificare le aree di stoccaggio più efficienti. Contiene le liste di prodotti e spazi, nonché la disposizione dei prodotti nel magazzino.

Le tre funzioni principali pianifica_disposizione_prodotti(), ottimizza_spazi() e visualizza_disposizione_prodotti() rappresentano le attività principali del processo di pianificazione e ottimizzazione degli spazi di un magazzino informatizzato utilizzando Python. La prima funzione definisce il modello di programmazione lineare utilizzando la libreria Pyomo, la seconda funzione risolve il modello e ottimizza gli spazi, mentre la terza funzione visualizza la disposizione dei prodotti all'interno del magazzino utilizzando la libreria Matplotlib.
