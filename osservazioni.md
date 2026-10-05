# Osservazioni — Esercitazione 0

Gruppo:Mignemi-Morelli

Componenti (nome, cognome e username GitHub di entrambi):
Carlotta Mignemi mignemi2249038-cell
Cristina Morelli morelli2266883

URL del repository coniviso:https://github.com/mignemi2249038-cell/esercitazione-0-template.git

Chi ha usato la tastiera nello step 1 e nello step 2:Morelli, Mignemi

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione:gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato:./hello sul terminale compare la scritta "Hello,computational physics!"

Che cosa ho capito su sorgente ed eseguibile:sulla sorgente modifico/scrivo il codice in c, l'eseguibile è il file gia compilato che mi mostrerà l'output sul terminale.

Output richiesto e comportamento del programma prima della modifica: è richiesto che l'output sia la frase scritta prima. Prima della modifica non viene stampata nessuna frase.

Esito dopo la modifica e spiegazione della correzione:sul terminale viene stampata la frase "Hello, computational physics!".

## Step 1 — Git

Quali file ho incluso nel commit e perché:sul commit abbiamo incluso il file modificato hello.c, perchè è l'unico che abbiamo modificato.

Come ho verificato che la versione provata sia presente su GitHub: siamo andate sul browser e abbiamo verificato che l'ultima modifica coincidesse con il momento dell'invio. Poi abbiamo aperto il file e controllato che le modifiche fossero presenti.

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone: il git pull va fatto per catturare le modifiche eseguite precedentemente, non serve fare nuovamente git clone poiché rimaniamo nella stessa repository.

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato: testo, intero e decimale, atoi per gli interi, atof per i decimali, ci stampa tutti e tre, quello che scrivimao dopo l'eseguibile-

Che cosa posso concludere: che l'arrey ha 4 elementi: eseguibile, testo inserito, intero e decimale.

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato: testo, intero e decimale, a differenza della precednete prova abbiamo utilizzato due funzioni per verificare che non ci fossero errori in input dal terminale. Scrivendo dopo l'eseguibile da terminale numeri intero o decimali in modo errato viene stampato l'errore.

Che cosa ho capito su testo, conversioni e stampa: dichiarando le variabili nel main come risultato delle funzioni applicate all'array argv[], abbiamo convertito l'input del terminale in variabili poi verificate dalle funzioni e stampate grazie a printf nel main.

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`: se in input da terminale vengono inseriti valori e testo validi l'eseguibile stampa nuovamente questi argomenti in output. Se viene inserita la parola "dodici" dopo l'eseguibile, al posto di un argoimento dell'intero o del decimale il programma ci stamperà errore perché non trova un valore numerico. Mentre se viene inseirita solo la parola "dodici" nel testo e non vengono inseriti altri argomenti il codice non arriva a leggere le funzioni e ci stampa sul terminale la guida di quello che dovremmo inserire.

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati: in eco2.txt viene salvato l'output che non viene più direttamente mostrato sul terminale. Se vengono inseriti gli argomenti sbagliati sul terminale compare la frase di testo di errore e sul file non viene salvato nulla.

Come un controllo automatico può riconoscere un errore:

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti: se modifico il codice devo ricompilare ed eseguire nuovamente. Se il codice è giusto e quindi rimane lo stesso e devo solo cambiare gli armenti non serve ricompilare, ma solo eseguire.


## Step 2 — Git

Come riconosco nella cronologia i commit dei due step: tramite i commenti associati ad ogni file, che descrivono i progrssi svolti.

Come ho verificato che la versione finale sia presente su GitHub: dal browser verifico la presenza dei file con le ultime modifiche aggiornate, apro i file per verificare ulteriormente che i codici all'interno coincidano.
