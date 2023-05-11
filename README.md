# Mersenne Twister in Python

## Introduzione:
Benvenuti alla presentazione del codice MersenneTwister, un generatore di numeri pseudo-casuali basato sull'algoritmo di Mersenne Twister. Questo codice è stato progettato per fornire una fonte affidabile e efficiente di numeri casuali all'interno delle vostre applicazioni.

## Caratteristiche principali:

1) Algoritmo di Mersenne Twister: Il generatore di numeri pseudo-casuali è basato sull'acclamato algoritmo di Mersenne Twister, noto per la sua eccellente qualità dei numeri casuali generati e la periodicità estremamente lunga.
2) Inizializzazione con seme: Il generatore può essere inizializzato con un seme specifico per riprodurre la stessa sequenza di numeri casuali. Questo è particolarmente utile per scopi di debug e test ripetibili.
3) Implementazione efficiente: Il codice è stato progettato con un'implementazione efficiente dell'algoritmo, garantendo una generazione rapida dei numeri casuali senza compromettere la qualità.
4) Interfaccia intuitiva: La classe MersenneTwister offre un'interfaccia chiara e intuitiva per l'uso. La generazione di numeri casuali e l'estrazione sono facili da comprendere e utilizzare.

## Struttura del codice
Il codice è organizzato come segue:

1) La classe `MersenneTwister` è stata definita come generatore di numeri casuali pseudo-casuali basato su Mersenne Twister.
2) Il costruttore `__init__` inizializza il generatore con un seme specifico.
3) Il metodo `initialize_generator` inizializza lo stato del generatore a partire dal seme fornito.
4) Il metodo `generate_numbers` genera una nuova serie di numeri casuali.
5) Il metodo `extract_number` estrae un numero casuale dal generatore.

## Utilizzo
Per utilizzare il generatore di numeri casuali MersenneTwister, seguire questi passaggi:

1) Importare la classe MersenneTwister nel tuo codice.
2) Creare un'istanza della classe MersenneTwister fornendo un seme come argomento.
3) Utilizzare il metodo extract_number per estrarre numeri casuali all'interno del tuo programma.

Ecco un esempio di utilizzo:
```# Importa la classe MersenneTwister
from MersenneTwister import MersenneTwister

# Crea un'istanza del generatore con un seme specifico
generator = MersenneTwister(seed=12345)

# Estrae un numero casuale
random_number = generator.extract_number()

# Utilizza il numero casuale nel tuo programma
print("Numero casuale generato:", random_number)
```

