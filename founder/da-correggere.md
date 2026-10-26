# Come leggere questo elenco

Tutto quello che il lavoro delle 11 skill ha trovato da **correggere** (cose
sbagliate o rotte) e da **migliorare** (cose che funzionano ma possono rendere
di più). È diviso per urgenza. "Chi" usa i ruoli proposti: **A** prodotto e
tecnica, **B** locali, **C** utenti e contenuti; i nomi li decidete voi.

| Priorità | Quando | Quante voci |
| --- | --- | ---: |
| Subito | entro il 1° novembre | 8 |
| Prima delle visite ai locali | entro il 9 novembre | 10 |
| Prima del lancio | entro il 3 dicembre | 11 |
| Dopo il lancio | dicembre 2026 – marzo 2027 | 9 |

# Subito (entro il 1° novembre)

## 1. Firebase: regole di sicurezza scadute

- **Problema:** Firestore e Realtime Database sono in "modalità test".
  L'accesso è scaduto (Firestore a luglio, Realtime Database ad agosto 2026):
  probabilmente l'app non legge né scrive più dati.
- **Cosa fare:** scrivere regole di sicurezza vere. Non prorogare la modalità
  test, che lascia i dati aperti a chiunque. Testare tutta l'app dopo.
- **Chi:** A · **Fonte:** email Firebase, board (tutti e tre i membri).

## 2. Database in Europa

- **Problema:** le FAQ promettono "server europei", ma nessuno ha verificato
  dove sono i database.
- **Cosa fare:** controllare la regione di Firestore e del Realtime Database in
  Firebase. Se non è in UE, correggere le FAQ o spostare i dati prima di avere
  utenti.
- **Chi:** A · **Fonte:** ops, FAQ v2.

## 3. Email di benvenuto con "[Company Name]"

- **Problema:** l'email "Nuova iscrizione Aroundly" contiene ancora il
  segnaposto del modello: "Welcome to the [Company Name] family!".
- **Cosa fare:** sostituirlo con "Aroundly" e tradurre l'email in italiano.
  Sarà la prima cosa che riceve chi entra in lista d'attesa.
- **Chi:** A · **Fonte:** email del 2 maggio 2026.

## 4. Il marchio "Aroundly"

- **Problema:** esiste già un'altra "Aroundly" in Italia, un'app turistica di
  Palermo (iInformatica Srls, 2017). aroundly.com è stato un'app di foto.
- **Cosa fare:** cercare "Aroundly" su UIBM, EUIPO e TMview nelle classi 9, 35,
  41 e 42. Se qualcuno l'ha registrato in classe 9, parlare con un consulente
  marchi prima di investire nel nome.
- **Chi:** C · **Fonte:** brand.

## 5. L'account Instagram

- **Problema:** a settembre il nome utente è passato da `aroundly.app` ad
  `aroundlyy`. La doppia "y" è difficile da dire a voce.
- **Cosa fare:** se il cambio non l'avete fatto voi, mettere subito in
  sicurezza l'account. Se era voluto, provare a recuperare `aroundly` o
  `aroundly.app` e aggiornare tutti i materiali.
- **Chi:** C · **Fonte:** email Instagram del 27 settembre 2026.

## 6. Scegliere la città

- **Problema:** il piano lavora su due regioni intere.
- **Cosa fare:** sceglierne una sola. La proposta è Padova; Udine se lì avete
  più contatti.
- **Chi:** tutti · **Fonte:** board, marketing.

## 7. Dividere i ruoli tra i soci

- **Problema:** non è scritto chi fa cosa.
- **Cosa fare:** assegnare i tre ruoli (tecnica, locali, utenti) e scrivere un
  patto tra soci: quote, tempo, cosa succede se uno esce.
- **Chi:** tutti · **Fonte:** ops, registro dei rischi.

## 8. Commercialista

- **Problema:** forma societaria, partita IVA e privacy non sono definite.
- **Cosa fare:** fissare un appuntamento e chiedere un preventivo vero (nel
  piano è stimato €80 al mese e €2.000 per la società).
- **Chi:** tutti · **Fonte:** CFO, ops.

# Prima delle visite ai locali (entro il 9 novembre)

## 9. Aprire la lista d'attesa

- **Cosa fare:** pagina "Stasera a Padova" e modulo sul sito dal 2 novembre.
  Chiedere città, fascia d'età, universitario sì/no, generi preferiti.
- **Obiettivo:** 300 iscritti prima delle visite ai bar, 1.000 prima delle
  discoteche.
- **Chi:** C · **Fonte:** marketing, launch, panel v3.

## 10. Conteggio della lista d'attesa sul telefono

- **Cosa fare:** una pagina da mostrare nelle visite con il conteggio in tempo
  reale, diviso per età, universitari e nuovi iscritti della settimana. Un
  numero che cresce convince più di un numero fermo.
- **Chi:** A · **Fonte:** offer, panel v3.

## 11. Togliere il vincolo di 3 mesi

- **Problema:** è il motivo di no più citato dopo "nessun utente".
- **Cosa fare:** mese per mese, nessun vincolo, in proposta, FAQ e script.
- **Chi:** B · **Fonte:** panel v1, board (Offerta).

## 12. Nuovi prezzi

- **Problema:** €50 / €150 / €250 sono al limite alto della fascia accettabile
  per ogni tipo di locale.
- **Cosa fare:** inserimento gratuito per tutti; Pro €39 e Club €119 solo dopo
  2.000 utenti attivi al mese.
- **Chi:** B · **Fonte:** pricing.

## 13. Togliere i prezzi barrati

- **Problema:** la proposta mostra €80 / €220 / €400 come "listino", ma non
  sono mai stati applicati. È un ancoraggio finto.
- **Cosa fare:** toglierli da proposta, FAQ e script.
- **Chi:** B · **Fonte:** pricing, regole di marketing.

## 14. Semplificare i pacchetti

- **Problema:** trailer video, 4 badge, mappa "avanzata" e report PDF per tutti
  sono troppo per un'app senza pubblico.
- **Cosa fare:** due piani (Pro, Club), descritti per risultato (persone
  raggiunte, biglietti venduti) prima delle funzioni.
- **Chi:** B · **Fonte:** board (Prodotto, Offerta), offer.

## 15. Aggiungere la garanzia

- **Cosa fare:** se in un mese pagato le serate fanno meno di 500
  visualizzazioni, il mese è gratis. Costa poco: circa €8 per locale al mese.
- **Chi:** B · **Fonte:** offer.

## 16. Riscrivere la proposta commerciale (v5)

- **Cosa fare:** nuova proposta con inserimento gratuito, soglia dei 2.000
  utenti, lista d'attesa, garanzia, prezzi nuovi, nessun vincolo.
- **Chi:** B · **Fonte:** offer.

## 17. Aggiornare lo script di vendita

- **Cosa fare:** nella fase Demo mostrare il conteggio della lista d'attesa.
  Nuove risposte alle obiezioni: "Quanti utenti avete?" → conteggio più "paghi
  solo dopo 2.000"; "Instagram è gratis" → "anche noi, finché non ti portiamo
  pubblico".
- **Chi:** B · **Fonte:** docs/aroundly.md, offer.

## 18. Aggiornare le FAQ

Le FAQ v2 contengono informazioni da correggere:

- **Vendita biglietti:** inclusa in Stage e Headline secondo le FAQ, assente
  nella proposta. Allinearle, e non promettere biglietti finché non è chiarita
  la parte fiscale (voce 21).
- **Setup Headline:** "veniamo direttamente da voi" non è nella proposta.
  Decidere se è una promessa.
- **Commissione sulle prevendite:** citata ma senza importo. Proposta: €0,50 a
  biglietto, da validare.
- **Gruppo partner:** nella proposta è in Stage, nelle FAQ in "Stage e
  Headline". Renderlo esplicito ovunque.
- **"Quanti utenti avete?":** aggiornare con la lista d'attesa.

**Chi:** B · **Fonte:** docs/aroundly.md (incongruenze).

# Prima del lancio (entro il 3 dicembre)

## 19. Calendario completo della città

- **Cosa fare:** caricare le serate di tutti i locali, anche quelli non
  partner, da fonti pubbliche. Obiettivo: almeno l'80% delle serate reali di
  ogni weekend.
- **Chi:** C · **Fonte:** board (Prodotto), ops.

## 20. Consenso scritto dei locali

- **Cosa fare:** prima di usare locandine e loghi, un consenso anche via
  messaggio. Rimozione immediata se un locale lo chiede.
- **Chi:** B · **Fonte:** ops.

## 21. Vendita biglietti: verifica fiscale

- **Problema:** in Italia i biglietti per intrattenimenti e locali da ballo
  hanno regole fiscali specifiche (biglietteria automatizzata, obblighi
  SIAE/Agenzia delle Entrate).
- **Cosa fare:** chiedere a un consulente se Aroundly può vendere biglietti o
  deve appoggiarsi a un sistema già autorizzato. Nessun biglietto in app prima.
- **Chi:** tutti · **Fonte:** ops.

## 22. Privacy e GDPR

- **Cosa fare:** informativa privacy, registro dei trattamenti, nomina di
  Google/Firebase come responsabile, consenso alla lista d'attesa,
  cancellazione dall'app.
- **Chi:** A · **Fonte:** ops, FAQ.

## 23. App sugli store

- **Cosa fare:** pubblicare su App Store e Google Play entro il 20 novembre. La
  revisione Apple può richiedere 1–2 settimane. Serve un account aziendale.
- **Chi:** A · **Fonte:** launch.

## 24. Etichetta "In evidenza" sugli sponsorizzati

- **Problema:** badge e posizioni a pagamento possono far sembrare il feed
  pubblicità.
- **Cosa fare:** ogni contenuto a pagamento porta l'etichetta "In evidenza", in
  rosa, e se ne mostrano pochi.
- **Chi:** A · **Fonte:** board (Prodotto), brand.

## 25. Misurare gli utenti

- **Cosa fare:** contare utenti attivi al mese e alla settimana, salvataggi e
  condivisioni per serata, iscritti che installano l'app. Senza questi numeri
  la soglia dei 2.000 non si può pubblicare.
- **Chi:** A · **Fonte:** marketing, launch.

## 26. Statistiche per i locali

- **Cosa fare:** visualizzazioni, salvataggi e condivisioni per serata, anche
  per chi è gratis. Sono la prova da mostrare quando si chiede di pagare.
- **Chi:** A · **Fonte:** panel ("I'd only keep paying if the dashboard gives
  me real numbers").

## 27. Ambassador e QR

- **Cosa fare:** 5–10 ambassador universitari con codici invito; adesivi QR nei
  locali partner. Codici diversi per sapere da dove arriva ogni utente.
- **Chi:** C · **Fonte:** marketing.

## 28. Prova con 30 amici

- **Cosa fare:** un weekend di uso reale prima del lancio; correggere quello
  che non va.
- **Chi:** tutti · **Fonte:** launch.

## 29. Preventivi veri

- **Problema:** quasi tutti i costi del CFO sono stime.
- **Cosa fare:** sostituire con preventivi: commercialista, costituzione,
  Stripe (verificare 1,5% + €0,25), Firebase, stampa. Poi rifare i conti.
- **Chi:** tutti · **Fonte:** cfo-sources.

# Dopo il lancio (dicembre 2026 – marzo 2027)

## 30. Controllare gli utenti ogni settimana

- **Allarmi:** meno di 300 utenti attivi a fine dicembre; copertura del
  calendario sotto il 60%; meno di 2 salvataggi per serata; meno del 30%
  degli iscritti che installa l'app.
- **Chi:** C · **Fonte:** launch.

## 31. Test del prezzo Pro

- **Cosa fare:** quando la città supera 2.000 utenti attivi, Pro a €29 per metà
  dei locali e a €39 per l'altra metà. Successo: almeno 8 locali paganti nel
  primo mese.
- **Chi:** B · **Fonte:** pricing.

## 32. Test del prezzo Club

- **Cosa fare:** €99 contro €149 con le prime 6–8 discoteche.
- **Chi:** B · **Fonte:** pricing.

## 33. Commissione sui biglietti

- **Cosa fare:** chiedere ai locali quanto pagano a Xceed o DICE, poi testare
  €0,50 contro €1,00. È l'entrata con più potenziale: non è ancora nei conti.
- **Chi:** B · **Fonte:** CFO, pricing.

## 34. Completare la ricerca sui concorrenti

- **Problema:** la ricerca web ha trovato poco su Veneto e Friuli; commissioni
  di Xceed e DICE non trovate.
- **Cosa fare:** 1–2 ore sugli store e su Instagram per le app e le pagine di
  eventi locali; chiedere ai locali cosa usano.
- **Chi:** C · **Fonte:** competitors.

## 35. Interviste vere ai proprietari

- **Problema:** tutte le risposte del panel sono simulate.
- **Cosa fare:** annotare dopo ogni visita obiezioni, interesse da 1 a 5,
  prezzo accettabile. Dopo 10 visite confrontarle con il panel.
- **Chi:** B · **Fonte:** consumer, script v4.

## 36. Nominare il vantaggio difendibile

- **Cosa fare:** scrivere in un paragrafo perché chi copia dopo sei mesi perde:
  densità (anche bar e serate gratis), dati, rapporto diretto con i
  proprietari.
- **Chi:** tutti · **Fonte:** board (Monopolio).

## 37. Costi Firebase sotto controllo

- **Cosa fare:** limiti di budget e avvisi in Google Cloud prima che il traffico
  salga.
- **Chi:** A · **Fonte:** ops.

## 38. Decidere sulla seconda città

- **Cosa fare:** solo dopo che la prima ha superato 2.000 utenti attivi e ha
  locali paganti. Rifare il panel e i conti per la nuova città.
- **Chi:** tutti · **Fonte:** board, marketing.
