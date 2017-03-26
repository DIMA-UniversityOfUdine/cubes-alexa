Report del progettino

L'obbiettivo che si è voluto raggiungere con questo progetto è stato quello di creare un piccolo video di presentazione della scena contenente un soggetto formato da soli cubi cui fosse stata associata un'animazione.
I possibili soggetti candidati per la scena sono stati principalmente quattro:
- svariati fiocchi di neve che scendono
- un cane
- una locomotiva
- un elicottero

La scelta è ricaduta sul cane che è stato prima realizzato in Unity (così da avere una prima versione del possibile prodotto finito e facilitare così i passi successivi).

Modificando il file StartingCode-withLights.html ed aggiungendo un'immagine alla cartella texture si è iniziato a replicare ciò che era stato realizzato in Unity per arrivare al prodotto finito.
Il cane è composto da 70 cubi di diverse dimensioni, appare in posizione seduta ed una texture (utilizzabile gratuitamente) è stata utilizzata per dare colore un colore marroncino al pelo. Naso e pupille sono stati realizzati con dei cubi neri, due cubi bianchi invece sono stati usati per la parte più grande dell'occhio. Può essere interessante notare la scelta della posizione delle pupille: esse infatti risultano spostate verso i lati esterni dei rispettivi occhi, dando ad uno spettatore frontale la sensazione di 'occhi a pesce'. Tale scelta è stata effettuata per migliorare l'aspetto del soggetto nel caso venisse osservato di profilo e con telecamera a tre-quarti, poichè con la pupilla completamente centrale l'occhio appariva 'vuoto' si visto non frontalmente.

In seguito è stata realizzata una semplice animazione: le orecchie del cane si sollevano e si abbassano leggermente mentre la coda si muove a destra e sinistra. Per fare ciò alcuni cubi sono stati usati come perni per delle semplici rotazioni il cui verso viene invertito dopo un certo lasso di tempo determinato da un contatore.

Anche alla telecamera è stata data un'animazione: essa infatti non risulta più controllabile dall'utente (il codice relativo a tale funzione è stato commentato non eliminato) ma orbita attorno al cane mantenendo l'obbiettivo sempre rivolto al soggetto stesso. Il codice usato è stato l'insieme di svariati tentativi personali integrati con le informazioni ottenute utilizzando materiale online (GitHub stesso e StackOverflow).

Infine utilizzando il programma (a licenza gratuita) Icecream Screen Recorder è stato realizzato un cortissimo video presentante la scena creata. Il file è di tipo webm.

Note per possibili aggiunte:
Sarebbe interessante completare la scena con un StartingCode-heightmap.html ed aggiungendo due animazioni ulteriori: una per le pupille degli occhi, di modo che si spostino secondo la posizione della telecamera, ed una seconda per simulare il movimento della lingua del cane (che dovrebbe essere aggiunta al modello di partenza).
