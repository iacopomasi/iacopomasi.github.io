---
layout: default
---

## Teaching (in 🇮🇹) <a name="teaching"></a>

### Teaching Philosophy

I strongly believe in Marshall McLuhan's words: 
> Anyone who tries to make a distinction between education and entertainment doesn't know the first thing about either.
In this sense, as an educator, I will do my best to ensure that my classes are as enjoyable as possible.

### Fondamenti di Programmazione AA 2020-2021, Canale 2 (MZ)

Il corso e' in collaborazione con lo stesso corso Canale 1 (AL) del [Prof. Andrea Sterbini](https://twiki.di.uniroma1.it/twiki/view/Programmazione1/AA20_21/WebHome).
Cerco di seguire le sue lezioni (il canale 2 per ora e' indietro rispetto al canale 1 di una sola lezione). Seguo i soliti esempi del Prof. Sterbini, ristrutturando gli esempi secondo la mia prospettiva.

### Libri di testo e risorse

I libri di testo consigliati sono i seguenti:
 - Allen B. Downey - [Pensare in Python](https://github.com/AllenDowney/ThinkPythonItalian/raw/master/thinkpython_italian.pdf)
 - Allen B. Downey - [Thinking in Python 2nd edition (in inglese)](https://greenteapress.com/wp/think-python-2e/)
 
 Altri libri (dalla corso gemello in inglese del [Prof. Di Ciccio](https://twiki.di.uniroma1.it/twiki/view/ACSAI/Programming/AA2021/WebHome) ):
 - Charles Dierbach [Introduction to Computer Science Using Python: A Computational Problem-Solving Focus](https://cs.kenyon.edu/pub/Main/IntroductiontoComputerScienceIdeas/Introduction_to_Computer_Science_using_Python__A_Computational_Problem-Solving_Focus_Dierbach_2012-12-25.pdf)
 - [Python 3 Tutorial](https://docs.python.org/3/tutorial/)

Altre risorse utili:
 - PEP 8 - [Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/) - Come scrivere codice elegante in python
 - PEP 257 - [Docstring Conventions](https://www.python.org/dev/peps/pep-0257/) - Documentazione con docstring
 

### Diario delle Lezioni e Materiale

> Per accedere e' necessario registrarsi a questo [Google Form](https://forms.gle/7BL8WBxp59WVb4ZN8) - compilabile solamente da studenti Sapienza.
> Cerco di aggiornare la lista il prima possibile, anche se <ins>l'accesso al materiale non è istantaneo. Una volta abilitati, riceverete un messaggio di benvenuto che vi conferma l'accesso</ins>.

#### "Common pitfalls" - cose da evitare:
1. Quando fate accesso ai link sottostanti <ins>assicuratevi di avere impostato su Google</ins> il vostro account Sapienza con email del tipo `cognome.123456@studenti.uniroma1.it`, grazie.
2. Se vi siete registrati tramite [Google Form](https://forms.gle/7BL8WBxp59WVb4ZN8) e immediatamente non riuscite ad accedere, <ins>per favore non richiedete accesso al documento tramite Google</ins>. Una volta iscritti, devo importare la vosta email nel gruppo: cerco di farlo il piu' velocemente possibile ma non e' istantaneo.

* **ven 6 nov, 8-10** (remoto): 
  - introduzione del docente, motivazione python;
  - recap su oggetti mutabili, immutabili, passaggio per riferimento; 
  - encoding e decoding; files di testo, open, with, read, readline, readlines, write, context manager;
  - file binari, lavorare con bit e byte, salvare un intero su file binario, convertire "a mano" con python binario a decimale, endianness;
  - cenni alla manipolazione di stringhe;
  - **Materiale**: 
    - [Zoom video + chat](https://drive.google.com/file/d/1qqHxsWUlLOrxEhwFotCj4bOe8Y7FgiKW/view?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1S_1tGkmgeHiRlVl6z0HXTGVM1LT14Vfp?usp=sharing)
* **mart 10 nov, 10-13** (remoto): 
  - programazione funzionale e iteratori;
  - funzioni come oggetti, passare funzioni a funzioni, ritornare funzioni;
  - Iteratori e Generatori come eager and lazy evaluation;
  - pack and unpack operators; funzioni con argomenti variabili args, kwargs;
  - programmazione funzionale in python (map, filter, any, all, lambda functions);
  - breve esempio di uso di iteratore zip() per unire due file;
  - **Materiale**: 
    - [Zoom video + chat](https://drive.google.com/file/d/1VO-JZjv4v3Jk1r2m_FxYqXUTwVwNDIhE/view?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/10BAlY4GGOraEHXcEUWYAhUKRCHDbiDbf?usp=sharing)
* **ven 13 nov, 8-10** (remoto): 
  - Definizione di Matrice;
  - Matrice come lista di liste;
  - Creare Matrici (vari metodi; da doppio ciclo a funzionale con map); Compound Object; Differenza fra Shallow e Deep Copy;
  - Immagini come matrici; spazio colori RGB; sistema di riferimento con matrici;
  - Disegnare su immagini/matrici (disegnare linee allineati agli assi, rettangoli, controllo per disegnare dentro matrice);
  - Cenni alla manipolazione di immagini (flip rispetto ad asse verticale e orizzontale, iterativo e funzionale);
  - **Materiale**: 
    - [Zoom video + chat](https://drive.google.com/file/d/1HNc0bh6wUtX7RI33JINpQvEqboLwgt0t/view?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1kGQ5oxxBISpHu2lX1_1LVgZPtr8iLz4X?usp=sharing)

* **mar 17 nov, 10-13** (modalita' mista): 
  - Chiarimenti enumerate e zip
  - Ancora su manipolazioni di immagini, flip verticale e orizzontale
  - `PEP 8` (code style) e `PEP 257` (doc string)
  - Ruotare una immagine, clockwise and counterclockwise; trasporre una matrice; versioni iterative e funzionali
  - Filtro di sfocatura (blurring)
  - Caso di applicazione: come sfuocare solo background similare al filtro di "Zoom" e affini
  - Programmazione orientata agli oggetti
  - Oggetti e classi in python; ereditarieta'
  - Esempio per modellare un colore non come tupla ma come classe
  - **Materiale**: 
    - [Zoom video + chat (files da scaricare)](https://drive.google.com/drive/folders/1d_S7u0n_ko4N_xLBREyq3tg7cjbNe8F2?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1K5WuO_ttCGxs7wVdTkbzPgXPAcTwj7hY?usp=sharing)
    
* **ven 20 nov, 8-10** (modalita' mista): 
  - Ancora sulla programmazione ad oggetti
  - Ripasso su cosa e' una classe; cosa e' un oggetto, attributi e metodi; classi in Python
  - Sottoclassi, ereditarieta', overloading degli operatori
  - Attributi di classi e attributi di instanza oggetto; metodi di classe
  - Breve cenni sui Decoratori in Python (con riferimento a `@classmethod`)
  - Gestione delle eccezioni in Python, costrutto `try except finally`.
  - **Materiale**: 
    - [Zoom video + chat](https://drive.google.com/drive/folders/164zu_5tOR1xafp4Ve0kzYjIvPY3dKTAM?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1zemFeWZaw9RkhQIR6P8O2pvuoqHAs9Dj?usp=sharing)
    
* **mar 24 nov, 10-13** (modalita' mista): 
  - Chiarimento su `HW6`
  - Chiarimento su overloading operatore `__eq__`
  - Package and module in python; come python cerca i moduli; `sys.path`
  - «Libreria» di elaborazione immagini con oggetti come un package da usare
  - Uso di decoratri per snellire il codice
  - Analisi della libreria e digressione sulle scelte di progettazione 
  - Il concetto di ricorsione; strutture dati coda (queue) e pila (stack); stack di un programma
  - Fibonacci ricorsivo e albero di ricorsione
  - **Materiale**: 
    - [Zoom video + chat](https://drive.google.com/drive/folders/16_fS02bfIv9e-5wE8JWu74QHOA46dexf?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1rGUf3oZR_TYthbKbDr7tSpTdlR3-B3Oo?usp=sharing)

* **ven 27 nov, 8-10** (modalita' mista): 
  - Precisazioni su come affrontare `HW`
  - Complessita' Fibonacci naive (ingenuo, versione di base); crescita esponenziale, esempio dei chicchi di grano su scacchiera
  - Fibonacci con "memoization"; cenni su dynamic programming (DP); Fibonacci iterativo
  - Sottoproblemi + caso base; divide and conquer
  - Esempio di uso di ricorsione per stampare una stringa senza for loop
  - Cenni al filesystem come albero di ricorsione 
  - **Materiale**: 
    - [Zoom video + chat](https://drive.google.com/drive/folders/17ao2iZVjk30RmU3c2xop8vyMHiH81I3d?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1oUpmkUP4bS7Fme_h2a2kZjNqheB5-0g6?usp=sharing)
    
<sub>Per favore se trovare errori o incongruenze, [fatemi sapere](mailto:masi@di.uniroma1.it) cosi aggiorno il materiale, grazie.</sub>
