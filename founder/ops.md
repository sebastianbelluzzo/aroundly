# Operazioni

Aroundly non ha magazzino né turni di cassa: le operazioni sono **tenere
completo e corretto il calendario**, **far funzionare l'app** e **seguire i
locali**. Tre soci, nessun dipendente.

## 1. Il ciclo di ogni giorno (◆ = lo vede l'utente)

1. Mattina: controllare Instagram e i canali dei locali della città per nuove
   locandine e cambi (DJ, orari, serate annullate).
2. Caricare o correggere le serate in app ◆ (obiettivo: ≥ 80% delle serate
   reali della città).
3. Pomeriggio: post "Stasera a Padova" ◆ (giovedì–sabato).
4. Rispondere a locali e utenti ◆ (entro 2 ore in orario serale).
5. Sera: controllo a campione che le serate di stasera siano giuste ◆.
6. Lunedì: statistiche della settimana ai locali (quando c'è la dashboard) ◆.

## 2. Fornitori e strumenti

| Cosa | Prodotto | Prezzo pubblico | Nota |
| --- | --- | --- | --- |
| Backend e database | Firebase (piano Blaze) | a consumo; quota gratuita 50k letture/20k scritture al giorno ([Firebase](https://firebase.google.com/docs/projects/billing/firebase-pricing-plans)) | ⚠️ regole in modalità test scadute: **da sistemare per prime**. Verificare che la regione del database sia in UE (promessa "server europei" delle FAQ) |
| Sito / pannello web | Netlify Pro | $20/mese ([fonte di terzi](https://kuberns.com/blogs/netlify-pricing/)) | Il gratuito può bastare all'inizio |
| Pagamenti abbonamenti | Stripe | ~1,5% + €0,25 per carte UE (da verificare su stripe.com) | Fatture elettroniche: serve un collegamento con SDI (es. Fatture in Cloud o il software del commercialista) |
| Biglietti | Integrazione esterna certificata (da scegliere) | da preventivo | ⚠️ vedi permessi |
| Store | Apple Developer €99/anno, Google Play $25 una tantum | prezzi pubblici | Serve un account aziendale per pubblicare a nome della società |
| Contabilità | Commercialista | stima €80/mese | Preventivo da chiedere |
| Comunicazione | WhatsApp Business, Google Workspace o Gmail | €0–7/utente | |
| Stampa QR e volantini | Tipografia online | ~€100 al lancio | |

Se un preventivo vero si discosta da `numbers.json`, aggiornarlo e rifare il CFO.

## 3. Persone: chi fa cosa

| Socio | Ruolo | Ore/settimana (stima) |
| --- | --- | --- |
| Socio A | **Prodotto e tecnica**: backend, app, sicurezza, dati | 15–20 |
| Socio B | **Locali**: visite, inserimenti, rapporti, contratti | 10–15 |
| Socio C | **Utenti e contenuti**: calendario, social, ambassador | 10–15 |

Nessuno stipendio previsto: il tempo dei soci non è nei costi del CFO. Se in
futuro si pagano compensi, contributi e forma vanno chiariti col commercialista.
I nomi vanno assegnati dai soci.

## 4. Procedure (SOP)

**A. Inserire un locale (gratuito)**
1. Visita o messaggio: spiegare in 2 minuti "gratis, carichiamo noi".
2. Raccogliere: nome, indirizzo, link social, tipo di serate, contatto WhatsApp.
3. Consenso scritto (anche via messaggio) a usare locandine e logo.
4. Creare il profilo, caricare le prossime serate, mandare il link al locale.

**B. Caricare una serata**
1. Locandina da Instagram del locale → titolo, data, ora, genere, DJ, prezzo.
2. Controllo incrociato con la storia o il post più recente.
3. Pubblicare; se cambia qualcosa, aggiornare subito.

**C. Gestire un reclamo**
1. Rispondere entro 2 ore: scuse e cosa si fa.
2. Correggere l'errore in app.
3. Annotare la causa nel registro; se si ripete, cambiare la procedura.

**D. Serata annullata**: togliere l'evento, avvisare chi l'ha salvato (notifica),
segnalarlo nel post del giorno.

**E. Revisione settimanale (lunedì, 30 min)**: copertura del calendario, utenti
attivi, salvataggi per serata, locali nuovi, reclami.

## 5. Licenze, permessi, obblighi (da confermare)

Le regole cambiano e dipendono dalla forma scelta: confermare ognuna con il
commercialista o l'ente indicato. Non è consulenza legale.

- **Società e partita IVA:** costituzione (SRL/SRLS o altra forma), iscrizione
  al Registro delle Imprese (Camera di Commercio), codice ATECO adatto (app,
  servizi pubblicitari). Fonte: [Registro Imprese](https://www.registroimprese.it).
- **Privacy/GDPR:** informativa privacy, registro dei trattamenti, nomina dei
  fornitori (Google/Firebase) come responsabili, conservazione dei dati in UE.
  Fonte: [Garante Privacy](https://www.garanteprivacy.it).
- **Fatturazione elettronica** verso i locali tramite SDI.
- ⚠️ **Vendita biglietti:** in Italia l'emissione di titoli d'accesso per
  spettacoli e intrattenimenti è soggetta a regole fiscali specifiche
  (biglietteria automatizzata, obblighi SIAE/Agenzia delle Entrate per i locali
  da ballo). Prima di vendere biglietti, verificare con un consulente se
  Aroundly può farlo direttamente o deve appoggiarsi a un sistema già
  autorizzato. Fonte da consultare: [Agenzia delle Entrate](https://www.agenziaentrate.gov.it).
- **Uso delle locandine e dei loghi dei locali:** consenso del locale (vedi SOP A).
- **Pubblicità:** i contenuti in evidenza a pagamento vanno segnalati come tali.

## 6. Registro dei rischi

| # | Rischio | Probabilità | Impatto | Piano |
| ---: | --- | --- | --- | --- |
| 1 | Backend non sicuro o fermo (già successo) | Alta | Alto | Regole di sicurezza vere prima del lancio; monitoraggio e backup |
| 2 | Calendario incompleto o sbagliato | Alta | Alto | SOP B, revisione serale, segnalazione errori in app |
| 3 | Pochi utenti dopo il lancio | Alta | Alto | Soglia d'allarme a fine dicembre (300 attivi): rivedere canali o città |
| 4 | Un socio esce o ha meno tempo | Media | Alto | Ruoli scritti, accessi condivisi, patto tra soci |
| 5 | Marchio "Aroundly" già registrato da altri | Media | Alto | Ricerca UIBM/EUIPO subito, nomi di riserva |
| 6 | Un locale si lamenta di una locandina usata | Media | Medio | Consenso scritto; rimozione immediata |
| 7 | Vendita biglietti non conforme | Media | Alto | Non vendere biglietti finché non è chiarito |
| 8 | Costi Firebase che salgono col traffico | Bassa | Medio | Limiti di budget in Google Cloud, avvisi |
| 9 | Xceed/DICE lanciano una funzione simile | Media | Medio | Densità: anche i bar e le serate gratis |
| 10 | Recensioni negative nei primi giorni | Media | Medio | Risposta entro un'ora, correzione visibile |
