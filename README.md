# ShowCoaching — prima versione del restyling

Sito statico per il repository Magopaolo-blip/showcoaching. HTML, CSS e JavaScript senza dipendenze. File pronti per GitHub Pages; dominio e DNS non configurati.

## Anteprima
Aprire index.html nel browser, oppure abilitare GitHub Pages dalla branch main, cartella root, dopo il caricamento. Tutti gli asset sono locali e i collegamenti relativi supportano /showcoaching/.

## Contenuti
Homepage, nove esperienze, biografia, testimonianze, contatti, 404. Filtri per pubblico, menu mobile e messaggio WhatsApp compilabile. Nessun invio automatico: WhatsApp apre un messaggio che l’utente rilegge e invia. Nessun analytics, font remoto o embed esterno.

## Prima versione, da rivedere con Paolo
- Nome Paolo Abozzi confermato. Testi del metodo da revisionare.
- Confermare disponibilità attuale dei nove format, loghi clienti e permessi sulle immagini/testimonianze.
- Numero WhatsApp confermato da Paolo: +39 328 292 4284. Link e modulo aprono WhatsApp in una nuova scheda, anche dall’anteprima incorporata.
- Laboratorio bolle: fonte contraddittoria (3/4 ore), mantenuto “da concordare”.
- Le immagini sono quelle del sito esistente; il ritratto di partenza è 300×300 e andrebbe sostituito con una foto ad alta risoluzione.
- Homepage e schede adattive presenti; verifica visuale browser desktop/mobile ancora da completare.

## Pubblicazione e migrazione — webmaster
1. Eseguire backup completo di WordPress e database e inventario URL, media, blog, shop e servizi attivi. Questa prima versione non migra blog e shop.
2. Revisionare i contenuti e completare informativa privacy, dati fiscali e informazioni societarie applicabili con dati confermati. Il sito statico non impiega analytics né cookie applicativi; il contatto rimanda a WhatsApp.
3. Verificare tutte le URL esistenti, conservare quelle necessarie o predisporre redirect reali sull’hosting di destinazione. GitHub Pages non gestisce redirect HTTP personalizzati: se necessari valutare hosting con supporto. Non usare 404 come sostituto sistematico dei redirect.
4. Configurare Pages e verificare l’anteprima all’URL comunicato da GitHub, prima di intervenire sul dominio.
5. Solo quando pronto: configurare dominio personalizzato, aggiungere CNAME e aggiornare i record web secondo le istruzioni correnti di GitHub. Conservare record mail MX, SPF, DKIM e DMARC, verificando eventuali dipendenze dall’IP del sito.
6. Attivare HTTPS, verificare www/apice e tutte le pagine principali.
7. Rimuovere il meta robots noindex dalle pagine di produzione, aggiungere canonical assoluti e sitemap per il dominio definitivo; verificare Search Console. Il noindex della BOZZA è intenzionale.
8. Ricontrollare contatti WhatsApp, menu mobile, filtri e leggibilità su dispositivi reali.

## Struttura
- index.html: homepage
- style.css / script.js: stile e interazioni condivise
- assets/: immagini locali ottimizzate
- cartelle dei format: pagine dettaglio con gli stessi slug del sito attuale
- FONTI.md: provenienza di testi e immagini

Non sono presenti CNAME, credenziali, configurazioni DNS o attivazioni di tracciamento.

## Video richiesti — in attesa dei file
- Winner Archery: sport.mp4
- Comunicare con lo ShowCoaching: schowcoaching.mp4
- Dentro una bolla di sapone: teambuilding.mp4
Inserimento previsto con player HTML5 orizzontale, controlli visibili e riproduzione manuale. I tre file non erano disponibili al momento di questa revisione; nessun player vuoto inserito.
