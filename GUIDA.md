# CV Editor: guida rapida

CV Editor serve a modificare il CV e la lettera di presentazione senza toccare LaTeX. Ogni modifica si vede subito nell'anteprima a destra.

## Primo avvio
1. Scarica l'app da [github.com/buzzo123/cv-editor-releases](https://github.com/buzzo123/cv-editor-releases) e installala:
   - **Mac**: apri il `.dmg` e trascina *CV Editor* in Applicazioni. La prima volta macOS dice che non può verificare l'app, perché non è firmata da Apple: premi **Fine** (non *Sposta nel Cestino*), apri **Impostazioni di Sistema → Privacy e sicurezza**, scorri fino a *Sicurezza* e premi **Apri comunque** accanto a "CV Editor", poi conferma con la password e di nuovo **Apri comunque**. Serve solo la prima volta. Gli aggiornamenti scaricati dall'app di solito si aprono senza questo passaggio; se macOS lo chiede di nuovo, si fa allo stesso modo.
   - **Windows**: esegui `CV-Editor-Setup.exe`. Se compare "Windows ha protetto il PC", scegli **Ulteriori informazioni → Esegui comunque**.
2. Apri **⚙ Impostazioni**, inserisci nome ed e-mail (servono a firmare le versioni) e fai **Accedi con GitHub**: si apre il browser, incolla il codice mostrato dall'app e autorizza.
3. Nella schermata iniziale scegli **Scarica** (il CV viene scaricato da GitHub nella cartella che scegli) oppure **Apri la cartella del CV…** se è già sul computer. Per partire da zero usa **Crea un nuovo CV…** (vedi sotto).

Dalla volta successiva l'app riapre da sola l'ultimo CV.

## Creare un nuovo CV
1. Nella schermata iniziale premi **Crea un nuovo CV…**. Succede lo stesso se con *Apri la cartella del CV…* scegli una cartella vuota.
2. Scegli la **Lingua del CV** (*Italiano*, *English* o *Français*; di partenza è quella del computer, oppure l'inglese se il computer è in un'altra lingua). Titoli delle sezioni, testi di esempio, lettera e data della lettera saranno in quella lingua, anche se l'app resta in un'altra.
3. Scegli come partire: **CV di esempio** (una voce d'esempio per sezione e una lettera traccia da sostituire) oppure **CV vuoto** (solo le sezioni: ognuna compare nel PDF appena aggiungi la prima voce).
4. Inserisci nome, cognome, e-mail e, se vuoi, la qualifica. Controlla **Dove salvarlo** (di solito *Documenti/CV_Nome_Cognome*) e premi **Crea il CV**.

L'app crea la cartella con tutto il necessario, attiva le versioni e salva la prima. Se la cartella scelta contiene già altri file, il CV va in una sottocartella nuova e nessun file esistente viene toccato.

## Modificare
- A sinistra ci sono le sezioni: **Aspetto** (colore e foto), **Intestazione** (nome, qualifica, contatti), le sezioni del CV, **Nota privacy** e **Lettera**.
- I testi supportano **grassetto** (⌘B / Ctrl+B) e *corsivo* (⌘I / Ctrl+I), con i pulsanti **G** e **C** che compaiono nel campo.
- Le voci (esperienze, titoli, punti elenco, competenze) si riordinano trascinando ⋮⋮ oppure con ↑ ↓. Con ⧉ si duplicano, con ✕ si eliminano.
- Una sezione si può nascondere togliendo la spunta *Mostra questa sezione nel CV*.
- Le modifiche vengono salvate da sole sul computer. **Annulla / Ripeti** sono le frecce in alto (oppure ⌘Z / ⇧⌘Z fuori dai campi).

## Colore e foto (Aspetto)
- **Colore primario**: scegli un colore dalla tavolozza, dal selettore o scrivendo il codice HEX. *Ripristina il colore originale* torna al colore iniziale.
- **Colore da un'immagine**: *Preleva un colore* trasforma il puntatore in un contagocce: clicca su un punto qualsiasi dello schermo (la foto, l'anteprima o il logo di un'azienda aperto in un'altra finestra), oppure Esc per annullare. Se il CV ha una foto, sotto *Colori della foto* trovi già i suoi colori principali.
- **Foto**: *Cambia foto…* → inquadra il viso (trascina e usa lo zoom) → *Usa questa foto*. Puoi scegliere cerchio o quadrato, il bordo e la posizione (sinistra o destra). *Reinquadra* riparte dalla foto originale.

## Lingua
In **⚙ Impostazioni → Lingua** scegli *Automatica* (la lingua del computer), *Italiano*, *English* o *Français*. Cambia i testi dell'app e i menu. La lingua di un CV nuovo si sceglie a parte, quando lo crei (vedi *Creare un nuovo CV*). Il contenuto dei CV già scritti non viene tradotto.

## Tema chiaro o scuro
In **⚙ Impostazioni → Tema dell'app** scegli *Automatico* (segue il computer), *Chiaro* o *Scuro*. Cambia solo l'aspetto dell'app: il CV nell'anteprima e nel PDF resta sempre su sfondo bianco.

## PDF
**Esporta PDF** (sopra l'anteprima) salva il PDF del documento mostrato (Curriculum o Lettera) dove preferisci.

## Salvare il CV su GitHub (una volta sola)
Un CV nuovo all'inizio è solo sul computer: la barra in basso dice *non collegato a GitHub*. Per averlo anche online premi **Sincronizza** (oppure *Collega…* in basso) e segui i tre passi:
1. **Accedi a GitHub** (se non hai un account, crealo gratis su github.com).
2. **Apri GitHub**: si apre la pagina per creare un repository, già compilata. Lascia **Private**, **non** aggiungere README, .gitignore o licenza e premi **Create repository**.
3. Copia l'indirizzo della pagina (https://github.com/…), incollalo nell'app e premi **Collega e invia**.

Da quel momento **Sincronizza** tiene allineato il CV online. Se hai già creato su GitHub un repository vuoto puoi anche usare **Scarica** con il suo indirizzo: l'app ti fa creare lì il nuovo CV e lo invia subito.

## Versioni e GitHub
- **Salva versione** (⌘S / Ctrl+S) crea una "fotografia" del CV con una breve descrizione e aggiorna anche i PDF nel repository.
- **Sincronizza** invia le tue versioni a GitHub e scarica quelle nuove. Se ci sono modifiche non ancora salvate, l'app ti chiede prima di salvare una versione.
- Se il CV è stato modificato sia qui sia altrove, l'app chiede se **tenere la tua versione** o **usare quella online**. L'altra versione non va persa: resta conservata in un branch di backup.
- **Cronologia** mostra tutte le versioni con l'anteprima del PDF. *Ripristina questa versione* la riporta come nuova versione, senza cancellare niente.

## Esportare e importare i contenuti
- **Esporta contenuti** (sopra l'anteprima, accanto a *Esporta PDF*, oppure nel menu *File*) salva in un file `.json` tutti i contenuti del CV: dati, sezioni, lettera, colore, lingua e foto. Niente impaginazione né PDF.
- Per ripartire da quel file: **Crea un nuovo CV…** → **Da un file** → **Scegli il file…**. Nome, cognome, e-mail e lingua vengono presi dal file e puoi cambiarli prima di premere **Crea il CV**.
- **Non hai il file?** Premi *Preparalo con un assistente IA*: l'app mostra un testo pronto, con un esempio. Copialo in ChatGPT, Claude o un altro assistente, incolla alla fine il tuo CV attuale (anche copiato da Word o da un PDF), salva la risposta in un file `.json` e importalo con *Da un file*. Ricorda che così il tuo CV viene inviato al servizio dell'assistente.
- Se il file ha un errore, l'app dice cosa non va (per esempio un campo mancante) e non crea niente.

## Aggiornamenti
- Quando esce una versione nuova, in cima alla finestra compare **È disponibile CV Editor …**. Premi **Novità e download** per vedere cosa cambia (l'elenco è in inglese) e poi **Scarica**.
- Finito il download, premi **Installa e chiudi CV Editor**. Su Mac si apre il disco della nuova versione: trascina *CV Editor* in *Applicazioni* e scegli **Sostituisci**. Su Windows parte l'installazione. Poi riapri l'app: il CV è salvato.
- **Più tardi** nasconde l'avviso fino alla prossima apertura dell'app.
- Puoi controllare quando vuoi con **Controlla aggiornamenti…** nel menu, oppure da **⚙ Impostazioni → Aggiornamenti**, dove puoi anche disattivare il controllo automatico.
