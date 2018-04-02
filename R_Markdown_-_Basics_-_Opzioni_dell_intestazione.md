Markdown - Basics - Opzioni dell'intestazione
================

-   [Introduzione](#introduzione)
    -   [R, Markdown, R Markdown...?](#r-markdown-r-markdown...)
    -   [File R Markdown](#file-r-markdown)
    -   [](#section)

Introduzione
------------

### R, Markdown, R Markdown...?

Il tutorial non è scritto in aramaico antico e siamo tutti abbastanza intelligenti da associare una definizione ad un termine. Perciò facciamo un po' d'ordine:

-   **R** è sia un *linguaggio di programmazione*<sup id="a1">[1](#f1)</sup> che un *ambiente di sviluppo*<sup id="a2">[2](#f2)</sup>

-   **Markdown** è un *linguaggio di markup*<sup id="a3">[3](#f3)</sup>

-   **R Markdown** è il nome del formato del file, con estensione .Rmd, su cui lavoreremo in RStudio

### File R Markdown

Un file .Rmd non è altro che un file di testo con al suo interno tre diverse tipologie di contenuti:

![Struttura\_file\_rmd](Struttura_file_rmd.png)

1.  Un'intestazione (o *header*) che fornisce le informazioni sul file e la sua struttura, necessarie durante la conversione da .Rmd ad altri formati (come vedremo più avanti). È racchiuso fra due stringhe di `---`

2.  Semplice testo

3.  Codice scritto in R<sup id="a4">[4](#f4)</sup>, racchiuso fra due stringhe di ```` ``` ````. Su Windows, questo carattere si ottiene utilizzando la combinazione di tasti `ALT` + `9` e `6` del tastierino numerico

In questo tutorial ci occuperemo di analizzare soltanto uno dei tre contenuti, cioé l'intestazione.

### 

#### Note

<i id="f1">1.</i> Ci vorrebbe un altro tutorial per spiegare cos'è e non è detto che a tutti interessi; in soldoni, si tratta di un linguaggio che definisice un set di regole che permette di interagire con una macchina ed ottenere da questa dei risultati. Non dite agli informatici che ho detto così o mi arrostiscono.[↩](#a1)

<i id="f2">2.</i> Stessa storia anche qui, potete pensarlo come un software che vi facilita la vita durante la scrittura del codice. Nel nostro caso, non usiamo R ma RStudio, molto più comodo.[↩](#a2)

<i id="f3">3.</i> Linguaggio basato su marcatori *(tags)*, serve a rappresentare la struttura di un testo: fa capire alla macchina qual è il titolo principale, quali sono gli elenchi, le tabelle e così via utilizzando i tags. Checché ne possiate pensare, markdown è uno dei linguaggi più ***semplici***.[↩](#a3)

<i id="f4">4.</i> N.B. RStudio permette di lavorare con più di un linguaggio di programmazione.[↩](#a4)
