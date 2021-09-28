---
layout: full
---

## Fondamenti di Programmazione AA 20-21, Can. 2 (MZ) (in 🇮🇹)<a name="fdp"></a>

### Codice OPIS per valutazione didattica  <a name="opis"></a>

Il mio codice OPIS |
--- |
`3IP2YMX0`  |


Inserirlo nella valutazione dei docenti seguendo [questa guida](https://www.uniroma1.it/sites/default/files/field_file_allegati/vademecum_per_studenti_opis_2020_21.pdf).

Il corso e' in collaborazione con lo stesso corso Canale 1 (AL) del [Prof. Andrea Sterbini](https://twiki.di.uniroma1.it/twiki/view/Programmazione1/AA20_21/WebHome).
Cerco di seguire le sue lezioni (il canale 2 per ora e' indietro rispetto al canale 1 di una sola lezione). Seguo i soliti esempi del Prof. Sterbini, ristrutturando gli esempi secondo la mia prospettiva.

### Libri di testo

I libri di testo consigliati sono i seguenti:
 - Allen B. Downey - [Pensare in Python](https://github.com/AllenDowney/ThinkPythonItalian/raw/master/thinkpython_italian.pdf)
 - Allen B. Downey - [Thinking in Python 2nd edition (in inglese)](https://greenteapress.com/wp/think-python-2e/)

 Altri libri (dalla corso gemello in inglese del [Prof. Di Ciccio](https://twiki.di.uniroma1.it/twiki/view/ACSAI/Programming/AA2021/WebHome) ):
 - Charles Dierbach [Introduction to Computer Science Using Python: A Computational Problem-Solving Focus](https://cs.kenyon.edu/pub/Main/IntroductiontoComputerScienceIdeas/Introduction_to_Computer_Science_using_Python__A_Computational_Problem-Solving_Focus_Dierbach_2012-12-25.pdf)
 - [Python 3 Tutorial](https://docs.python.org/3/tutorial/)

Altre risorse utili:
 - PEP 8 - [Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/) - Come scrivere codice elegante in python
 - PEP 257 - [Docstring Conventions](https://www.python.org/dev/peps/pep-0257/) - Documentazione con docstring


### Sessione Straordinaria per gli esami di profitto
Rimando al link ufficiale per prenotazioni [Modulo iscrizione sessione straordinaria](https://www.studiareinformatica.uniroma1.it/modulo-sessione-straordinaria-appelli)
```
Riservata a studenti part-time, fuori corso nell’A.A. 2020-2021, studenti genitori,
studenti con disabilità e con D.S.A, LAUREANDI (si intende studenti con
tesi /tirocinio formalmente avviati),  per i nostri corsi di studio agli
studenti lavoratori in grado di dimostrarlo, non è a carico di Sapienza ma dello studente.
```

### Risorse, Tools e Guide addizionali generiche e di coding in python <a name="guide"></a>
Per essere dei buoni programmatori e muovervi velocemente col calcolatore, dovete disimparare quello che avete imparato naturalmente fino ad ora. Quindi, almeno quando programmate, cercate di minimizzare il piu' possibile uso di GUI (Graphical User Interface) e mouse, e cercate di aumentare utilizzo di:
  - Tastiera
  - Combinazioni da tastiera (memorizzatene il piu possibile), usate anche i comandi a destra come Home, Page Down, Page Up etc che vi consentono di muovervi velocemente. Cmq sia e' imperativo conoscere bene le shortcuts della vostra IDE (Integrated Development Environment).
  - Editor testuali avanzati o IDE

Altra regola d'oro e' che per programmare vi serve solamente:
  - Editor di testo un minimo avanzato (synthax highlight, suggerimenti, documentazione o `help()`)
  - Interprete come `ipython` per provare snippet di codice che create e verificare passo passo che le funzionalita' che create via via sono correttte (fondamentale!).
  - Debugger (integrato nella IDE) altrimenti potete usare il modulo `pudb` (more on this later)
  - Pagine di carta + una penna o lapis su dove annotare idee o algoritmi o casi basi o degenere etc.
  - La `vostra mente`, dedicata a voi al completo, quindi priva di [distrazioni](https://imgur.com/gallery/3uyRWGJ) quali facebook, whatsapp, messenger o qualsiasi evento asincrono che vi toglie attenzione. Evento asincrono puo' anche essere arbitrariamente il vostro cane che abbaia e vi chiede la pappa. Piu' riuscite a minimizzare le interruzioni, piu' farete progressi. Quindi regola d'oro quando studiate o programmate: chiudete il piu' possibile fonte di distrazioni da eventi esterni, vi dovete assorbire completamente nello studio. Per tenere traccia del tempo potete utilizzare un `timer`. Sia per tracciare tempo che passa sia per misurare quanto ci impiegate a risolvere gli esercizi.

Andare per piccoli passi:

**Nota Importante:** Se state passando da mondo Windows e vi volete avventurare in *nix, andate per gradi e seguite questo ordine:
```
1. Installazione dual-boot Win-Linux (occhio a non rovinare l'installazione Windows).
2. Prendere confidenza con distro Linux scelta
3. Sapere interagire col terminale: un test per capire se uno e' a suo agio con il terminale
   e' rispondere alla seguente domanda
   "Se ti e' dato un computer che ha solo il terminale senza GUI, ci sai lavorare?"
   Se la risp e' si puoi andare avanti;
4. Passare a programmare in Spyder e quando si e' sicuri, passare ad
   editor piu' tosti come Emacs
```

Settings e Tools:

  - **[Sistema Operativo]** <ins>E' fortemente consigliato</ins> l'uso di sistemi [*nix-based](https://upload.wikimedia.org/wikipedia/commons/7/77/Unix_history-simple.svg) quali GNU/Linux, MacOSX. <ins>Prima iniziate ad usare sistemi *nix-based e meglio e', meno problemi avrete nella vostra carriera. Quindi consiglio e' INIZIATE ORA subito che siete giovani!</ins>
Come distribuzioni GNU/Linux vi consiglio fortemente distribuzioni basate su Debian quali [Debian](http://www.debian.org), [Ubuntu](https://www.ubuntu-it.org) o [Mint](https://linuxmint.com) (in ordine di difficolta' discendente). Potete usare Windows ma non e' consigliato e cmq c'e' sempre opzione dual-boot con Linux.
 - **[Bash Linux primer]** Per muoversi abilmente in un sistema *nix e' essenziale avere confidenza con il terminale. Solitamente un interprete di base per il terminale (un po' come interprete `python`) e' interprete di comandi da terminale [`bash - Bourne Again SHell`](https://www.gnu.org/software/bash/). Una guida di base per partire con bash e' [UNIX Command Line section](https://barbagroup.github.io/essential_skills_RRC/nix/setup/) di questo gruppo di ricerca. Vi trovate anche qualcosa su Python.
 - **[IDE]** Personalmente non sono un grande fan delle "IDE" perche' mascherano quello che succede dietro i comandi, diciamo che per apprezzare le IDE bisogna prima capire quello che c'e' dietro e poi usarle. Se uno fa il processo contrario (le usa senza sapere cosa c'e' dietro) rischia di incasinarsi ancora di piu. Tendenzialmente, i compromessi fra le due soluzioni sono: 1) con le IDE, si impara subito ma magari mascherano cosa accade sotto e si tende ad anadare piu lenti se si usa molto il mouse; 2) se si usa un editor da terminale e' molto piu' ostico e difficile all'inizio, ma se si impara poi si programma molto velocemente). Per il corso si puo' usare:
   - **[Facile, Consigliato]**  [Spyder IDE](https://www.spyder-ide.org) con interprete ipython disponibile tramite installazione conda `conda install spyder`. Se usate un'IDE mi raccomando di avere coscienza di quello che IDE vi fa automaticamente dietro; cmq sia Spyder e' ben fatto. Un esempio: IDE vi mette a disposizione istruzioni/funzioni/moduli che su python non vi sono: provate ad usare `runfile` semplicemente eseguendo `python -c "help(runfile)"` da terminale oppure ad eseguire `help(runfile)` dall'interprete in Spyder. Che succede?
   - **[Difficile, per rompersi la testa]** Iniziare a programmare da terminale con [Emacs](https://www.gnu.org/software/emacs/) con supporto a python tramite [Elpy](http://elpy.readthedocs.io) e [Flycheck](https://www.flycheck.org/en/latest/) per controllo sintassi e suggerimenti code PEP8 compilant. [Emacs Wiki](https://www.emacswiki.org/emacs/SiteMap), [Schema comandi da tastiera Emacs (da incollare davanti al muro)](https://sachachua.com/blog/2013/05/how-to-learn-emacs-a-hand-drawn-one-pager-for-beginners/)
 - **[Debug]** Debuggare un programma e' importantissimo e potete usare 1) debuggare integrato di Spyder che usa `ipdb` oppure 2) a me personalmente piace usare [`pudb`](https://pypi.org/project/pudb/) installabile con `conda install -c conda-forge pudb`. Per usare `pudb` dopo averlo installato, semplicemente invocare python con il modulo pudb e il file principale `main.py` che si vuole debuggare con `python -m pudb main.py`. Per usare in maniera efficiente `pudb` e' necessario configurarlo e <ins>imparare le scorciatoie da tastiera per debuggare rapidamente</ins>.
 - **[Python]** Altre risorse interessanti di python meno formali:
   - [Python tips](https://book.pythontips.com/en/latest/index.html)
   - [Python reference](https://python-reference.readthedocs.io/en/latest/index.html)
   - [Collections](https://docs.python.org/3.8/library/collections.html) Strutture dati un piu' avanzate ma cmq disponibili in python
   - [Python Cheatsheet](https://gto76.github.io/python-cheatsheet/)


### Ricevimento Studenti <a name="ricevimento"></a>
Ho attivato l'orario di ricevimento. Possiamo fare una prova per vedere se questo meccanismo che ho creato puo' funzionare.
<ins>Nel caso vedo che non e' flessibile abbastanza o ci sono problemi, ci potrebbero essere variazioni in futuro.</ins>

**Nota:** Cercate di essere parsimoniosi col ricevimento: usate il [q2a forum](https://q2a.di.uniroma1.it)
per risolvere problemi banali o chiedere aiuto, in generale. Potete anche provare a scrivermi una email ma
come mezzo e' molto lento (possono passare alcuni giorni priam che risponda). Nel caso in cui vi sentite persi,
oppure avete bisogno di un chiarimento di un concetto visto a lezione, fatene uso del ricevimento.

La procedura per prenotare il ricevimento e' la seguente:

```
Ricevimento studenti disponibile su prenotazione.
30 min per ogni studente o per ogni gruppo di studente
che affrontano lo stesso problema/chiarimento.

Il ricevimento si svolgera' tramite Zoom, **che deve essere creato dallo studente.**
```

Seguire scrupolsamente queste istruzioni:

0. **Gli slot devono essere richiesti con un minimo di anticipo quindi richiesti <ins>venerdi per il martedi</ins>**
1. Prenotare uno slot di 30 min tramite Google Calendar: [https://bit.ly/3pbU2fv](https://bit.ly/3pbU2fv)
2. Dentro il campo "What" / "Cosa" inserire il **a) vostro nome b) argomento del chiarimento o ripasso**
3. Inserire nel campo "where"/"dove" il link zoom che avete creato
4. Useremo il link zoom creato per fare il ricevimento diverso da ogni studente/gruppo di studenti
5. Ci vediamo al vostro Zoom link creato per quel orario/giorno.


### Diario delle lezioni con materiale:

#### Accesso al materiale e cose da evitare per ottenere accesso: <a name="access"></a>
> Il form che vi era prima è deprecato. Se volete accedere al materiale dovete iscrivervi al Google Classroom di Fondamenti di Programmazione AA21-22. Fornisco il codice a lezione.
> Chi è iscritto al classroom dovrebbe poter accedere direttamente a questo materiale con la solita email con cui si è iscritto al  Classroom.

#### Materiale:

* **ven 6 nov, 8-10** (remoto):
  - introduzione del docente, motivazione python;
  - recap su oggetti mutabili, immutabili, passaggio per riferimento;
  - encoding e decoding; files di testo, open, with, read, readline, readlines, write, context manager;
  - file binari, lavorare con bit e byte, salvare un intero su file binario, convertire "a mano" con python binario a decimale, endianness;
  - cenni alla manipolazione di stringhe;
  - **Materiale**:
    - [Zoom video + chat](https://drive.google.com/drive/folders/1kR1FYy_AyNrG_nIVJ-eFxCM32XTRrcO2?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1S_1tGkmgeHiRlVl6z0HXTGVM1LT14Vfp?usp=sharing)
* **mart 10 nov, 10-13** (remoto):
  - programazione funzionale e iteratori;
  - funzioni come oggetti, passare funzioni a funzioni, ritornare funzioni;
  - Iteratori e Generatori come eager and lazy evaluation;
  - pack and unpack operators; funzioni con argomenti variabili args, kwargs;
  - programmazione funzionale in python (map, filter, any, all, lambda functions);
  - breve esempio di uso di iteratore zip() per unire due file;
  - **Materiale**:
    - [Zoom video + chat](https://drive.google.com/drive/folders/1A0PYH9HBlRbQDL2LsVvVO2u0savF9Xke?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/10BAlY4GGOraEHXcEUWYAhUKRCHDbiDbf?usp=sharing)
* **ven 13 nov, 8-10** (remoto):
  - Definizione di Matrice;
  - Matrice come lista di liste;
  - Creare Matrici (vari metodi; da doppio ciclo a funzionale con map); Compound Object; Differenza fra Shallow e Deep Copy;
  - Immagini come matrici; spazio colori RGB; sistema di riferimento con matrici;
  - Disegnare su immagini/matrici (disegnare linee allineati agli assi, rettangoli, controllo per disegnare dentro matrice);
  - Cenni alla manipolazione di immagini (flip rispetto ad asse verticale e orizzontale, iterativo e funzionale);
  - **Materiale**:
    - [Zoom video + chat](https://drive.google.com/drive/folders/1kGQ5oxxBISpHu2lX1_1LVgZPtr8iLz4X?usp=sharing)
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

* **mar 24 nov, 10-13** (modalita' mista): <a name="imagemat"></a>
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
  - `callable` objects in python and the overloading of `__call__`
  - Esempio di uso di ricorsione per stampare una stringa senza for loop
  - Cenni al filesystem come albero di ricorsione
  - **Materiale**:
    - [Zoom video + chat](https://drive.google.com/drive/folders/17ao2iZVjk30RmU3c2xop8vyMHiH81I3d?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1oUpmkUP4bS7Fme_h2a2kZjNqheB5-0g6?usp=sharing)

* **mar 01 dic, 10-13** (modalita' mista):
  - Valutazione docente, codice [`OPIS`](#opis)
  - Breve cenno su **non** modificare moduli nel HW
  - _[Ricorsione]_ Riassumere come stampare stringa carattere per carattere senza for
  - _[Ricorsione]_ Espressioni Return and Pass
  - _[Ricorsione]_ Filesystem come albero di ricorsione
  - _[Ricorsione]_ Stringa palindroma (iterativa, ricorsiva)
  - _[Ricorsione]_ Albero binario, ricerca in un albero, debug con `pudb` della ricerca
  - **Materiale**:
    - [Zoom video + chat](https://drive.google.com/drive/folders/18LeXKag56zYoACzx4PwJbS6_6LwyOmY8?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1Pnve6ZNz0s2EgKJf1kmKQLeSvEHZIhn3?usp=sharing)

* **ven 4 dic, 8-10** (modalita' mista):
  - Filosofia di studio e sulla preparazione all'esame
  - Annuncio che faccio lezione anche al canale 1
  - Come creare un iteratore alla classe [`imagemat`](#imagemat) per modellare matrici
  - Analisi di come funziona `TraceRecursion` del [Prof. Sterbini](https://twiki.di.uniroma1.it/twiki/view/Programmazione1/AA20_21/WebHome)
  - Breve recap di Iterator, Iterable, Generator; funzioni con argomenti variabili `(args, kwargs)`
  - _[Ricorsione]_ Enumerare (e ottenere) le permutazioni di un insieme come problema ricorsivo
  - _[Ricorsione]_ Ricerca in profondita' (depth-first-search) `DFS` (pre/in/post order) su albero binario
  - _[Ricorsione]_ Espressioni aritmetiche come albero binario (navigarle in pre/in/post)
  - **Materiale**:
    - [Zoom video + chat](https://drive.google.com/drive/folders/1SA733Rp8ej5OBQAARZmkHzn89rY3kDok?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1pZWdzBM11_Kgf5fzegqO-TBb2Qg1tw_h?usp=sharing)

* ~~**mar 8 dic, 10-13**~~  (Festa Immacolata Concezione)

* **ven 11 dic, 8-10** (modalita' mista):
  - Recap del `HW6`
  - Consigli strategici su come affrontare gli `HW` e gestire il tempo
  - Analisi del problema `HW6` e possibili modi per risolverlo, idee varie e schemi di soluzione
  - Analisi dei dati forniti
  - Ripasso di immagini/matrici come lista di liste (differenza fra accesso riga e colonna)
  - Importanza di come si scrivere il codice e il suo stile
  - Analisi nel dettaglio della soluzione e del codice dello studente [Simone Sestito](http://simonesestito.com) (`1937764`). Lo ringrazio vivamente per aver fornito il suo codice.
  - Cenni a DAG (Direct Acyclic Graph)
  - **Materiale**:
    - [Zoom video + chat](https://drive.google.com/drive/folders/1regFUbAB6coipR6SDdKEbiyKV8qlN2tu?usp=sharing)
    - [Slides (pdf)](https://drive.google.com/drive/folders/1RXFkXgM6_rilh53ftMhFujCuzlxi0xOU?usp=sharing)

* **mar 15 dic, 10-13** (modalita' mista):
  - Ripasso su `callable` objects
  - Ripasso su `*args, **kwargs`
  - Un nostro `defaultdict` (usare con attenzione e cautela)
  - Chiarimenti aggiuntivi su `TraceRecurision` (basati su `__call__`)
  - Espressioni aritmetiche come albero binario
  - Concetto di parser e grammatica
  - Creare un parser per espressioni aritmetiche con albero binario
  - Gestione parentesi
  - Gestione espressione e split in token
  - Parser completo di Espressione Aritmetiche
  - Risoluzione e Print della espressioni in-order
  - Analisi soluzione di `HW6` codice Prof. Sterbini
  - **Materiale**:
    - [Zoom video](https://drive.google.com/drive/folders/1ALkCHCEtPASA0n94jhbB7RfxZwg-lmKT?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1jc-nDPx3sp_MbgcHaTQ9DJOTzVx9OwRG?usp=sharing)


* **ven 18 dic, 8-10** (modalita' mista):
  - Da albero **Bi**nario ad albero **N**-ario
  - Branching factor di un albero
  - Ripasso del Filesystem come albero N-ario con branching factor variabile
  - Recap Ricorsione per calcolo permutazioni, ma con analisi branching factor e complessita'
  - Albero di Gioco: `Nodo : Stato = Arco : Mossa`; Albero di gioco come albero N-ario.
  - Esempio di "enumerazione" delle mosse possibili nel gioco del filetto con ricorsione
  - Indicizzazione della scacchiera solamente con `[]` e `slice` e.g. `A[:,c]` seleziona colonna `c-th`.
  - Stesura del codice modulare per enumerazione mosse filetto
  - Brevissimi cenni a soluzione di `HW8`  Prof. Sterbini
  - **Materiale**:
    - [Zoom video](https://drive.google.com/drive/folders/1AeV55orjMSkKA0vp4cwyzPo062UnPdQq?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1BBunJ76LsoB_LAX_MxctEWEmzO3KbuKi?usp=sharing)

* **mar 22 dic, 10-13** (recupero, remoto)
  - Analisi dettagliata soluzione di `HW8` codice Prof. Sterbini
  - Alcune varianti su come risolvere parte `HW8` come enumerazione di stati di un Automa Stati Finiti
  - Analisi complessita' dell esempio `HW8` esponenziale
  - Da versione ricorsive a come si scrivere una versione iterativa
  - Ripasso su Alberi di Gioco
  - Cenni al modulo python `argparse` per gestire input complessi in ingresso
  - Breve introduzione a `Jupyter Notebook`
  - Auguri di Buone Feste
  - **Materiale**:
    - [Zoom video](https://drive.google.com/file/d/1ffe3KksTMT7my0r7GL9LERbmbdOv16Qa/view?usp=sharing)
    - [Slides e IPython/Notebook (py,pdf,html)](https://drive.google.com/drive/folders/1zpjaMUQG6jFZIoYofXqnzSl1PjHBftYk?usp=sharing)


<sub>Per favore se trovare errori o incongruenze, [fatemi sapere](contact) cosi aggiorno il materiale, grazie.</sub>
