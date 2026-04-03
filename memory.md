# Memory — Portfolio Personale Gabriele Siani

---

## Sessione del 02/04/2026

### Cosa abbiamo fatto
- Creata la struttura completa del progetto (cartella, CLAUDE.md, brand-assets)
- Definito lo stile: Dark & Bold — sfondo #080D1A, accento blu elettrico #4B6BFB, font Playfair Display + DM Sans
- Costruito il sito completo (index.html) con tutte le sezioni

### Decisioni prese
- Stile Dark & Bold scelto da Gabriele tra tre opzioni proposte
- Portfolio dual-purpose: acquisire clienti web + opportunità come Marketing Manager
- Nessuna menzione dell'AI nella realizzazione del sito
- Anno nel footer: 2026
- Distinzione visiva tra Progetto Universitario (badge grigio) ed Esperienza Professionale (badge verde)
- L'account hotel da 200K+ follower va presentato come gestione professionale senza specificare che è della ragazza — formulazione: "struttura hospitality"
- Progetti fittizi da aggiungere progressivamente nelle sessioni future

### Struttura del sito
- **Hero** — nome, titolo, CTA, tre numeri chiave
- **Chi sono** — bio + card dati personali
- **Competenze** — tre colonne (Marketing Digitale, Social Media, Web Design) + strip tool. Animazione barre: 0.7s
- **Lavori selezionati** — 5 progetti con badge categoria + badge Universitario/Professionale:
  1. Ferrari — Brand Positioning (Universitario) → link a ferrari.html
  2. Kinder — Campagna Social Ferrero (Universitario) → link a kinder.html
  3. Instagram — +2.000 follower in 45 giorni (Professionale)
  4. Tesi — Guerrilla vs Marketing Tradizionale (Universitario, in corso)
  5. Hotel — Gestione Social 200K+ (Professionale, in corso)
- **Risultati** — contatori animati
- **Contatti** — form + email + LinkedIn

### Problemi risolti
- Animazioni troppo lente: ridotta durata barre competenze da 1.5s a 0.7s, stagger progetti da 0.15s a 0.08s
- Pagina nera al ritorno dalla pagina interna: fix con ScrollTrigger.refresh() su window load
- Script GSAP con defer rompevano opacity:0 — rimosso defer da tutti i file

### File presenti
- index.html — homepage
- ferrari.html — case study Ferrari (interviste Maranello, modello One Ferrari)
- kinder.html — case study Kinder Pinguì (strategia social Ferrero, mockup visivi CSS, solo Gabriele nel team)

### Sito online
- GitHub: https://github.com/Gabrieletech0/portfolio-gabriele-siani
- Vercel: https://portfolio-gabriele-siani.vercel.app/index.html
- Per aggiornare: git add . && git commit -m "modifica" && git push

---

## Sessione del 03/04/2026 (prima parte)

### Cosa abbiamo fatto
- Creata pagina federvini.html — case study completo della campagna FederVini per consumo responsabile
- Creata pagina napoli.html — case study "100 Giri di Passione" per il centenario SSC Napoli + Marshall
- Aggiunta homepage con i nuovi progetti FederVini e SSC Napoli nella sezione Lavori selezionati
- File non ancora pushati su GitHub

---

## Sessione del 03/04/2026 (seconda parte)

### Cosa abbiamo fatto
- Redesign completo dell'index.html per renderlo più professionale
- Aggiunta foto reali nelle card dei progetti (immagini Unsplash con zoom on hover)
- Aggiunta sezione Blog con 3 articoli placeholder (AI & Marketing, Guerrilla vs Marketing, Instagram Growth) con foto di copertina reali
- Aggiunta sezione Newsletter con form email funzionante (pronto per collegare Brevo/Mailchimp)
- Mantenute le pagine federvini.html e napoli.html dalla sessione precedente (già complete e coerenti)

### Decisioni prese
- Le card dei progetti ora hanno immagini reali anziché solo iniziali tipografiche
- Blog ha 3 post con stato "PROSSIMAMENTE" — pronti per quando Gabriele scriverà il contenuto
- Newsletter placeholder: il form mostra un messaggio di conferma ma non è ancora collegato a un servizio
- I 4 case study principali (Ferrari, Kinder, FederVini, Napoli) occupano 2 righe da 2 card grandi
- I 3 progetti minori (Instagram, Hotel, Tesi) restano come card più piccole nella terza riga

### Struttura attuale del sito
- **Hero** — headline "Marketing Strategist", CTA, stats strip, indicatore scroll
- **Chi sono** — bio + card profilo con info personali
- **Competenze** — 3 colonne con skill bar animate + strip strumenti
- **Progetti** — 4 case study grandi con foto + 3 card minori
- **Risultati** — contatori animati + 3 card esperienza
- **Blog** — 3 articoli con thumbnail foto, tag, tempo lettura
- **Newsletter** — form iscrizione con conferma
- **Contatti** — info + form contatto
- **Footer** — logo, copyright, link

### File presenti
- index.html — homepage (redesign con foto, blog, newsletter)
- ferrari.html — case study Ferrari
- kinder.html — case study Kinder
- federvini.html — case study FederVini (campagna consumo responsabile)
- napoli.html — case study SSC Napoli (100 Giri di Passione)
- brand-assets/ — brand guidelines + PDF originali dei progetti universitari

### Prossimi step
- Push su GitHub per mettere online tutto (Vercel si aggiorna in automatico)
- Collegare la newsletter a Brevo o Mailchimp
- Aggiungere foto profilo reale di Gabriele (attualmente placeholder "G")
- Scrivere contenuti per i 3 articoli del blog
- Collegare il form contatto a un servizio (Formspree, EmailJS, etc.)

---

## Sessione del 03/04/2026 (terza parte)

### Cosa abbiamo fatto
- Aggiunto banner CTA "Cerchi un sito web professionale?" nella sezione Progetti dell'index.html (link a webdesign.html)
- Creata pagina webdesign.html con: galleria 4 siti web, sezione processo di lavoro (4 step), pricing con 3 pacchetti (Starter 299€, Professional 599€, E-commerce 999€), CTA finale
- Fix immagine Kinder nella homepage (sostituita con foto cioccolato più pertinente)

### Decisioni prese
- Portfolio è dual-purpose: marketing + web design (Gabriele vuole vendere siti web)
- La pagina webdesign.html include 4 esempi di siti: portfolio personale, Moda Mare Italia, ristorante (landing page), studio professionale (corporate)
- Pricing trasparente con 3 fasce — i prezzi sono indicativi, personalizzabili
- I siti esempio 3 e 4 (ristorante e studio) sono placeholder/esercizi di stile — non ancora realizzati

### File presenti (aggiornamento)
- index.html — homepage con banner web design
- ferrari.html — case study Ferrari
- kinder.html — case study Kinder
- federvini.html — case study FederVini
- napoli.html — case study SSC Napoli
- webdesign.html — pagina servizio web design con galleria + pricing
- brand-assets/ — brand guidelines + PDF

### Prossimi step
- Push su GitHub per mettere online tutto
- Collegare newsletter e form contatto
- Foto profilo reale
- Creare siti di esempio reali (ristorante, studio) per rendere la galleria più credibile
- Sostituire gli screenshot placeholder con screenshot reali dei siti
- Scrivere articoli blog

---

## Sessione del 03/04/2026 (quarta parte)

### Cosa abbiamo fatto
- Creata pagina tesi.html — case study completo della tesi magistrale con: hero, overview stats, domanda di ricerca, 4 framework teorici, 4 ipotesi H1-H4, matrice 2x2 del disegno sperimentale, processo di ricerca, struttura 3 parti / 10 capitoli, CTA finale
- Creata e salvata skill `skills/case-study-writing.md` — best practice per scrivere case study per portfolio web (cercate sul web e salvate)
- Collegata la card "Tesi" nell'index.html alla nuova pagina tesi.html con link "LEGGI DI PIU'"
- Corretto testo Instagram: l'account non partiva da zero ma era bloccato — aggiornato sia nella card progetto che nell'articolo blog
- Rimosso cursore lampeggiante dopo "Marketing Strategist" nell'hero
- Le card Ferrari e Kinder usano iniziali tipografiche (F e K) come preferito da Gabriele, non foto

### Decisioni prese
- Gabriele preferisce le iniziali tipografiche nelle card dei progetti (F, K) rispetto alle foto Unsplash
- L'account Instagram era bloccato, non partito da zero — formulazione corretta: "Account bloccato riportato in crescita"
- Niente cursore lampeggiante nell'hero

### File presenti (aggiornamento)
- index.html — homepage
- ferrari.html — case study Ferrari
- kinder.html — case study Kinder
- federvini.html — case study FederVini
- napoli.html — case study SSC Napoli
- tesi.html — case study tesi magistrale
- webdesign.html — pagina servizio web design
- brand-assets/ — brand guidelines + PDF

### Prossimi step
- Push su GitHub per mettere online tutto
- Collegare newsletter (Brevo/Mailchimp) e form contatto (Formspree/EmailJS)
- Aggiungere foto profilo reale di Gabriele
- Scrivere articoli blog
- Creare siti di esempio reali per la pagina web design

---

## Sessione del 03/04/2026 (quinta parte)

### Cosa abbiamo fatto
- Implementato toggle lingua IT/EN su TUTTE le 7 pagine del sito: index, ferrari, kinder, federvini, napoli, tesi, webdesign
- Ogni pagina ha un bottone "EN" / "IT" nella navbar che switcha tutti i testi
- La scelta della lingua si salva in localStorage e si sincronizza tra le pagine
- Creata e salvata skill `skills/case-study-writing.md` con best practice per scrivere case study
- Creata pagina tesi.html — case study della tesi magistrale
- Creata pagina webdesign.html — servizio web design con galleria + pricing
- Aggiunto banner CTA web design nella homepage
- Fix: "stage estero" → "stage all'estero"
- Fix: rimosso cursore lampeggiante dall'hero
- Fix: testo Instagram corretto (account era bloccato, non partito da zero)
- Fix: Ferrari e Kinder tornati a iniziali tipografiche (F e K) come preferito da Gabriele
- Rimosso articolo blog "+2.000 follower" — Gabriele non lo voleva

### Decisioni prese
- Gabriele preferisce le iniziali tipografiche (F, K) nelle card rispetto alle foto
- L'account Instagram era bloccato, non partito da zero
- "COMING SOON" usato anche in italiano (comprensibile nel contesto web)
- Toggle lingua implementato con data-en attributes + localStorage
- Tesi e webdesign: toggle già applicato dagli agenti prima che Gabriele dicesse di non farli ora

### Implementazione tecnica toggle lingua
- Ogni elemento testuale ha un attributo `data-en="English text"`
- Per elementi con HTML interno: `data-html="true"` per preservare il markup
- Per placeholder di input: `data-en-placeholder="English placeholder"`
- Script JS: `toggleLang()` switcha, `applyLang()` applica, localStorage persiste
- Il bottone mostra "EN" quando sei in IT e "IT" quando sei in EN

### File presenti
- index.html, ferrari.html, kinder.html, federvini.html, napoli.html, tesi.html, webdesign.html
- Tutti con toggle IT/EN funzionante
- skills/case-study-writing.md — nuova skill

### Prossimi step
- Push su GitHub per mettere online tutto
- Collegare newsletter e form contatto
- Foto profilo reale
- Scrivere articoli blog
- Creare siti di esempio reali per la pagina web design
