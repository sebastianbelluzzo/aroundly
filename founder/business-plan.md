# Aroundly · Business plan

**Verdict: Not yet**

- ✓ Each locale pagante al mese earns $60.80 before fixed costs (97% contribution).
- ✗ Year 1 operating LOSS: $2,440.
- ✓ Break-even is 11 locale pagante al meses a day against a capacity of 150.
- ✗ 1 of 20 simulated buyers buy (5%, the bar is 25%).

| key number | |
| --- | ---: |
| Price | $63.00 a locale pagante al mese |
| Profit margin at plan | 71% per locale pagante al mese |
| Break-even | 11 locale pagante al meses a day |
| Year 1 operating profit | $-2,440 |
| Startup spend | $2,973 |
| Cash needed before it pays for itself | $6,951 |
| Startup money earned back | not in year 1 |
| Buyer panel | 1 buy · 19 pass |

## The idea

- What it is: an app for local nightlife. People who want to go out open it and
  see what is on tonight near them (clubs, DJ sets, events, bars with music
  nights) on a map and a live calendar, with the full flyer (time, DJ, genre,
  price), and can save, share or buy entry.
- Who it is for: two sides. **Payers:** owners of nightlife venues in Friuli
  Venezia Giulia and Veneto (bars with evening events, venues with DJ sets,
  nightclubs). **Users (free):** people roughly 18 to 35 in the same area who
  go out at night and today look for events on Instagram, Google, Telegram
  groups and word of mouth.
- What it sells, at what price: monthly subscriptions for venues, launch prices
  (list prices in brackets), plus VAT 22%:
  - Venue, for bars: €50/month (€80). Profile linked to socials, unlimited
    events, basic map position, guided setup.
  - Stage, for venues with DJ sets: €150/month (€220). Closer map position, 2
    "Recommended" badges a month, follower notifications + 1 area push a month,
    basic dashboard, partner group, ticket sales.
  - Headline, for nightclubs: €250/month (€400). 4 events at the top of the home
    a month, 4 "Trending" badges, advanced map, 4 area pushes, event video
    trailer, advanced dashboard + PDF report, ticket sales.
  - Terms: first month free (no card), then 3 paid months minimum, monthly
    auto-renewal, cancel with 30 days' notice. Launch price locked for early
    partners. A separate commission on ticket pre-sales (amount not set yet).
- Where and how: Friuli Venezia Giulia and Veneto, Italy. Sold door to door by
  the founders with a partner kit (proposal, script, FAQ): first month free,
  demo on the phone. The app is built on Firebase and hosted on Netlify. Pre-launch:
  the app is not public yet and has no user base.
- Budget and constraints: three co-founders. €200 to €1,000 a month of spending
  (excluding founders' time). No outside funding mentioned. The core risk the
  founders already know: a two-sided market (venues pay only if there are users,
  users come only if there are venues).

Full details in Italian: `docs/aroundly.md`.

## Summary

**Verdetto (calcolato): NOT YET.** Due controlli non passano: l'anno 1 chiude
in perdita (−€2.440) e solo 1 proprietario simulato su 20 compra (5%, la soglia
è 25%). Cosa deve cambiare: **portare utenti in una città prima di chiedere
soldi ai locali** (`/founder-launch`, `/founder-marketing`), poi verificare con
locali veri il prezzo Pro €29–39 (`/founder-pricing`).

**Cos'è:** Aroundly è un'app che mostra tutte le serate di stasera vicino a te
(mappa, calendario, locandina completa). La pagano i locali di Friuli e Veneto
con un abbonamento mensile; gli utenti la usano gratis.

**I tre numeri (modello v2, euro, IVA esclusa):**
- Margine per locale: €60,80 su €63 di canone medio (~97%).
- Pareggio: 11 locali paganti al mese (costi fissi ~€634 al mese).
- Anno 1: −€2.440 di gestione, −€5.413 dopo le spese iniziali; servono ~€7.000
  di cassa.

**Board e panel d'accordo su:** il problema non è il prezzo né il margine, è il
mercato a due lati. Oggi l'app non ha utenti e il backend è fermo, quindi
nessun locale paga (11 no su 20 per "fiducia"). Con l'offerta nuova (gratis,
paghi dopo 2.000 utenti, nessun vincolo) 19 locali su 20 accettano di entrare
gratis: il calendario si può riempire.

**Dove non sono d'accordo:** il board vuole meno funzioni e un solo piano
pagante; il panel di discoteche accetterebbe un piano più ricco (€119). Il
prezzo giusto per i bar (€25–39) va trovato con un test.

**Il rischio più grande:** non arrivare a 2.000 utenti attivi in una città.
Cosa si fa: una sola città (Padova consigliata), calendario completo riempito
dai soci, contenuto "Stasera a Padova", ambassador universitari, QR nei locali;
soglia d'allarme a 300 attivi a fine dicembre.

**Per partire servono:** ~€7.000 tra i tre soci (circa €2.300 a testa), il
backend sistemato, e due test a novembre: ≥ 30 locali su 50 accettano
l'inserimento gratuito, ≥ 500 iscritti alla lista d'attesa.

**La cosa da fare questa settimana:** sistemare le regole di sicurezza di
Firebase e rimettere in funzione l'app. Senza, nient'altro può partire.

Il panel è composto da acquirenti simulati e i numeri sono proiezioni con molte
stime: clienti veri e preventivi veri li confermano. Non è consulenza
finanziaria, legale o fiscale.

## What the board said

**Voto: 3 FUND IF su 3 · punteggio medio 4/10**

| Prospettiva | Punteggio | Voto |
| --- | --- | --- |
| Offerta (da *$100M Offers*) | 4/10 | FUND IF |
| Monopolio (da *Zero to One*) | 4/10 | FUND IF |
| Prodotto (dalla biografia di Steve Jobs) | 4/10 | FUND IF |

Le tre prospettive applicano framework pubblicati; non sono quelle persone e
non parlano a loro nome. Memo completi in `founder/board/`.

### I rischi sollevati da più membri (prima di tutto)

1. **Nessun utente, quindi niente da vendere** (tutti e tre). Si chiede ai
   locali di pagare per una visibilità verso un pubblico che non c'è ancora.
   "Quanti utenti avete?" è l'obiezione che decide la vendita, e oggi la
   risposta è zero. Con una mappa vuota anche gli utenti cancellano l'app.
2. **Il backend non funziona** (tutti e tre). I database Firebase sono rimasti
   in modalità test e l'accesso è scaduto in estate. Una demo che fallisce in
   una scena regionale piccola brucia il passaparola.
3. **Troppo, troppo presto** (Monopolio, Prodotto, in parte Offerta). Tre
   pacchetti, badge, notifiche, trailer, report PDF, biglietteria: il menu di
   una piattaforma pubblicitaria matura, su due regioni, con €200–1.000 al
   mese. La densità in una città è l'unico vantaggio difendibile, e due regioni
   la disperdono.
4. **Il rischio è tutto sul locale** (Offerta). Si vendono funzioni, non
   risultati; nessuna garanzia; 3 mesi di vincolo dopo il mese gratis.

### Dove non sono d'accordo

- **Prezzi:** l'Offerta chiede di non abbassarli ma di aggiungere prova e
  garanzia; il Prodotto vuole ridurre tutto a un annuncio gratuito più un solo
  pacchetto a pagamento.
- **Annunci a pagamento:** il Prodotto avverte che badge "Consigliato" e
  "Di tendenza" possono far sembrare il feed pubblicità e rovinare la fiducia
  degli utenti; l'Offerta li considera leve di valore se c'è un pubblico.
- **Il vantaggio:** il Monopolio dubita che l'idea sia dieci volte migliore di
  una buona pagina Instagram di eventi e chiede di nominare il fossato; gli
  altri due si concentrano sull'esecuzione.

### Condizioni (checklist per il resto del pacchetto)

- [ ] **Backend sistemato e sicuro**, app pubblica, prima di far pagare
      qualunque locale. (ops, launch)
- [ ] **Una sola città** fino a quando non è densa. (marketing, launch)
- [ ] **Utenti prima dei pagamenti:** riempire da soli il calendario di quella
      città (eventi pubblici, gratis per i locali) per almeno un mese di
      weekend, poi misurare utenti attivi settimanali, salvataggi e
      condivisioni. (launch, marketing)
- [ ] **Fissare la soglia di utenti** oltre la quale un locale paga. (cfo,
      pricing)
- [ ] **Togliere il rischio al locale:** gratis o solo commissione all'inizio,
      oppure garanzia misurabile; niente vincolo di 3 mesi finché non c'è prova.
      (offer)
- [ ] **Pacchetti riscritti sui risultati** (persone raggiunte, biglietti
      venduti), con meno funzioni. (offer, pricing)
- [ ] **Fissare la commissione sulle prevendite.** (pricing, cfo)
- [ ] **Annunci a pagamento segnalati come sponsorizzati e limitati.** (brand,
      offer)
- [ ] **Nominare il fossato** in un paragrafo: densità della rete, dati,
      biglietteria. (competitors, plan)
- [ ] **Prima prova pagante:** conversione e rinnovo dopo il periodo minimo da
      un primo gruppo di locali. (launch)

### La versione più forte che il board vede

Non è quella presentata. Aroundly è prima di tutto **il calendario completo
della notte in una città** (Padova o Udine, per esempio), riempito dai
fondatori stessi dalle locandine pubbliche finché gli utenti non trovano ogni
weekend tutto quello che c'è. I locali entrano gratis, perché un calendario
completo li vuole tutti. Quando la città ha un pubblico misurabile, si vende ai
locali un solo pacchetto semplice (in evidenza + statistiche) e si guadagna
sulle prevendite. Poi si replica città per città. L'offerta a tre livelli con
badge e trailer arriva dopo, quando c'è un pubblico da mostrare.

## The competition

Ricerca del 26/10/2026, solo fonti pubbliche, ogni fatto con link. Dove una
fonte non dava il dato lo segno come "non trovato": non è stato inventato
niente. Limite importante: la ricerca web ha trovato poco materiale specifico
sulla nightlife di Veneto e FVG; una verifica a mano sugli store e su Instagram
(1–2 ore) completerebbe il quadro.

### 1. Chi c'è

| Nome | Tipo | Dove | Cosa vende | Cosa costa al locale |
| --- | --- | --- | --- | --- |
| **Instagram** (profili + boost) | Sostituto | Ovunque | Post, storie, sponsorizzate | Gratis l'organico; boost a pagamento |
| **Gruppi Telegram/WhatsApp, PR** | Sostituto | Canali privati | Liste, passaparola | PR pagati a ingresso (importi non pubblici) |
| **Xceed** | Diretto | App; Milano e grandi città UE ([Wikipedia](https://en.wikipedia.org/wiki/Xceed_(company))). Veneto/FVG non confermati | Biglietti, tavoli VIP, liste ([App Store](https://apps.apple.com/app/id955085811)) | Commissione sui biglietti (importo non trovato) |
| **DICE** | Indiretto | App; presente a Padova, es. [Hall Padova](https://dice.fm/venue/hall-padova-evv6) | Biglietti concerti/serate, strumenti di marketing per organizzatori ([Il Post](https://www.ilpost.it/2022/10/10/dice-app-social-concerti/)) | Commissione (importo non trovato) |
| **Zero.eu** | Indiretto | Magazine: Padova, Venezia, FVG ([es. Factory Club Padova](https://zero.eu/it/luoghi/234458-factory-club-padova,padova)) | Guida a locali ed eventi | Non trovato |
| **Eventbrite** | Indiretto | Ovunque, generalista ([Udine](https://www.eventbrite.com/d/italy--udine/udine/)) | Biglietteria e scoperta eventi | Commissioni definite "alte" da utenti ([Capterra](https://www.capterra.it/reviews/114949/eventbrite)) |
| **Fever** | Indiretto | Verona, Venezia ([Fever Verona](https://feverup.com/it/verona/eventi-musicali)) | Esperienze, concerti Candlelight (~€28), tour | Non trovato |
| **Facebook Events** | Indiretto | Ovunque | Pagine evento | Gratis |
| **Party** (app) | Diretto | iOS, copertura non verificata ([App Store](https://apps.apple.com/to/app/party-app/id6466177765)) | Mappa discoteche con eventi | Non trovato |
| **Disco Link** | Diretto | iOS, copertura non verificata ([App Store](https://apps.apple.com/py/app/disco-link/id6462903257)) | Prenotazione tavoli, eventi in corso | Non trovato |

Dati completi in `founder/competitors.csv`.

### 2. Fascia di prezzo per il locale

Non confrontabile in modo diretto: **nessun concorrente trovato vende un
abbonamento mensile di visibilità ai locali.** Il modello del settore è la
**commissione sui biglietti** (Xceed, DICE, Eventbrite) oppure **gratis**
(Instagram organico, Facebook, magazine). Il canone di Aroundly (€50–250 al
mese) è quindi una categoria nuova per il locale, e va giustificato con dati.

### 3. Mappa di posizionamento

Assi: **copertura della nightlife locale** (quanti eventi della zona) e
**specializzazione sulla notte**.

```
                   specializzati sulla notte
                            ▲
        Xceed, DICE         │      [SPAZIO VUOTO:
        (grandi città,      │       tutte le serate di una
         solo eventi con    │       città, anche bar e
         biglietto)         │       serate gratis]
                            │        ← Aroundly punta qui
 copertura ─────────────────┼──────────────────────► copertura
 bassa                      │                         alta
        Party, Disco Link   │      Instagram, Facebook
        (copertura ignota)  │      (c'è tutto, ma disperso)
        Fever, Eventbrite   │      Zero.eu (curato, parziale)
                            │
                   generalisti
```

### 4. Lamentele dei clienti (temi)

Materiale scarso, quindi tutti i temi sono **deboli** (meno di tre recensioni
ciascuno):

- **Rimborsi decisi dall'organizzatore** (Xceed): l'azienda risponde che "Refund
  policies are determined by the organizers" ([Trustpilot](https://ie.trustpilot.com/review/xceed.me)).
  Biglietti non rimborsabili salvo ingresso negato ([Xceed Milano](https://xceed.me/it/milano/event/one-more-time-3/236408)).
- **App e biglietti difficili da recuperare** (Xceed iOS): un utente segnala
  problemi a collegare l'email e recuperare il biglietto ([mwm.ai](https://mwm.ai/de/apps/xceed-we-go-out/955085811)).
- **Commissioni alte** (Eventbrite) per eventi a pagamento ([Capterra](https://www.capterra.it/reviews/114949/eventbrite)).
- **Dal lato locale**, le lamentele su Instagram (organico in calo, boost non
  misurabili) vengono dai materiali dei fondatori, non da fonti pubbliche:
  vanno confermate con i proprietari.

### 5. Il buco (the gap)

**Nessuno mette in un solo posto tutte le serate di una città di Veneto o
Friuli**, comprese quelle senza biglietto (bar con DJ set, serate gratis, liste).
I ticketing (Xceed, DICE) coprono solo eventi con prevendita e soprattutto le
grandi città; Zero.eu è curato ma parziale; Instagram ha tutto ma disperso e
senza ricerca per "stasera, vicino a me".

Dato di contesto: nel 2025 in FVG le discoteche erano seconde per incassi
nello spettacolo, con 3.119 eventi, €11,9 milioni e oltre un milione di presenze
([Il Nord Est, rapporto SIAE](https://www.ilnordest.it/economia/imprese/rapporto-siae-friuli-concerti-veneto-vinitaly-kesi7cm6)).
Il mercato c'è; resta da capire quanto i locali spendano in promozione.

### 6. La minaccia

- **Xceed o DICE** che aggiungono la mappa "stasera vicino a te" in Veneto: hanno
  già app, utenti e rapporto con i club. Sono i più veloci a copiare.
- **Una pagina Instagram locale di eventi** con molti follower: costi zero, già
  pubblico. È il concorrente più probabile nel giorno per giorno.
- Difesa: **densità** (tutti i locali di una città, anche i piccoli che i
  ticketing ignorano) e **relazione diretta** con i proprietari.

## The buyer panel

**1 buy · 19 pass** (5% buy) out of 20 simulated buyers. Seed 7, so the same cards can be dealt again.

These are simulated buyers, not customers. Use this to find objections and weak spots, then confirm the big ones with real people before you spend.

### By segment

| group | buyers | buy rate |
| --- | ---: | ---: |
| Owner or manager of a venue with weekly DJ sets | 6 | 17%  (thin) |
| Owner or marketing manager of a nightclub | 4 | 0%  (thin) |
| Owner of a bar or pub with music nights a few times a month | 10 | 0% |

### By buying behaviour

| group | buyers | buy rate |
| --- | ---: | ---: |
| Data-curious | 3 | 33%  (thin) |
| Relies on PR and lists | 4 | 0%  (thin) |
| Burned before | 3 | 0%  (thin) |
| Instagram does it all | 5 | 0%  (thin) |
| Early adopter | 2 | 0%  (thin) |
| Cost cutter | 3 | 0%  (thin) |

### By income

| group | buyers | buy rate |
| --- | ---: | ---: |
| $53,000 and up | 7 | 14%  (thin) |
| $36,000 to $53,000 | 7 | 0%  (thin) |
| under $36,000 | 6 | 0%  (thin) |

### Why they pass

| reason | buyers | in their words |
| --- | ---: | --- |
| trust | 11 | "My nights get filled by my PR guys and the WhatsApp lists, not by an app nobody has installed yet. A free month is nice, but I'm not signing a 3-month minimum with a startup that has zero users." (P001) · "I've already paid for a promo platform that brought nobody, and Instagram does the job for free. An app that isn't even public yet has no users, so why would I pay for it?" (P002) |
| price | 3 | "I fill my nights with PR people, WhatsApp lists and my regulars, not apps. Fifty euro a month plus VAT for three months minimum is real money on my margins, and I don't know if anyone in my town will open an app that isn't even public yet." (P006) · "A monthly fee with a 3-month minimum is too much for a bar like mine, and my friend already does the Instagram while the PR guys fill the lists. I'd try the free month maybe, but I wouldn't commit to paying." (P008) |
| habit | 3 | "I already put every flyer on Instagram and stories and it works well enough, and my friend does it for me. I don't need another place to post, and I'm not paying for an app nobody is using yet." (P011) · "I already post my DJ nights on Instagram and I don't have time to manage another platform. An app nobody uses yet isn't going to fill my room, and students already find out about the nights through Instagram and word of mouth." (P015) |
| timing | 1 | "I clear 28 grand a year and every monthly fee gets cut unless it fills the room, and I've got no proof an app nobody uses yet will bring people in on a Friday. I'm not signing a 3-month minimum for something that isn't even public." (P012) |
| need | 1 | "I already post every flyer on Instagram and stories, my friend handles it and the PR guys fill the lists, and it works well enough. An app nobody uses yet doesn't give me anything extra, and my competitors will be on it too." (P016) |

### Why they buy

| reason | buyers | in their words |
| --- | ---: | --- |
| need | 1 | "The first month is free with no card, so I'd try Stage and let them load my DJ nights. I'd only keep paying if the dashboard gives me real numbers, which boosts never do." (P018) |

### What would flip a no

- Proof of real users in my area (thousands of downloads in Friuli/Veneto) and a pilot with no 3-month lock-in, or a couple of other clubs I know already on it.
- Proof of real users in my area, such as a few thousand people already using it in Friuli, or a couple of venues like mine saying it filled their nights. Or a free or pay-per-ticket deal with no minimum.
- Proof that real people in my area open it on a Friday night, for example a few thousand active users in Friuli, or a venue like mine showing numbers on how many people came because of it. Then I'd happily take the free month.
- Proof of real students opening it in my area, like a few thousand active users in Trieste, Udine or Padova, and a way to get exclusive placement over rival clubs in my town. A pay-per-ticket-sold deal with no monthly fee would also do it.
- Seeing real numbers: students in my city actually using the app, and a few venues like mine who got people through the door from it. Or no minimum commitment while it proves itself.
- Seeing the app already used by people in my area, or a free tier or no minimum commitment so I can just try it with no risk.
- Real numbers: a few thousand active users in my area, or a trial month where I can see people coming through my door because of the app.
- No 3-month minimum (month to month) at the Venue price, plus proof from a few bars that it brings real people in, with clear numbers.
- Proof of real users in my area (thousands of downloads in Friuli/Veneto, or venues like mine reporting people who came through it), plus a free listing or a no-minimum trial so I can see it bring in people first.
- Proof of real users in my area and a pay-per-result or no-minimum deal (cancel anytime), or a free plan until the app actually has people using it.
- Seeing real numbers of local users in my area, and a few venues I know already on it getting people through the door. Then I would take the free month and see.
- Seeing the app live with real people in my area using it, and a month with no fee and no minimum where they load the nights for me and I can see whether anyone actually came because of it.

Buyers say they would buy **1.0 times** in the first month on average.

20 buyers gave all four price answers. Run founder-pricing's van_westendorp.py on the answers folder.

## Pricing

Fonti: le quattro risposte sul prezzo dei 20 proprietari simulati
(`pricing-curve.md`, `panel/by-segment/*.md`), i concorrenti
(`competitors.md`) e i numeri del CFO (`cfo.md`). I prezzi sono in euro al mese,
IVA esclusa. Il tool stampa "$" ma i valori sono euro.

### 1. Cosa hanno detto i proprietari (simulati)

| Segmento | Risposte | Fascia accettabile (PMC → PME) | Prezzo "di minor resistenza" | Prezzo attuale | Dove cade |
| --- | ---: | --- | ---: | ---: | --- |
| Bar con serate | 10 | €15 → €60 | €15–30 | Venue €50 | Dentro, ma vicino al tetto |
| Locali con DJ set | 6 | €40 → €151 | €40–90 | Stage €150 | Sul tetto |
| Discoteche | 4 | troppo poche per la curva | — | Headline €250 | Per 4 su 4 €250 è già "caro" (€180–250); "troppo caro" a €300–400 |
| Tutti insieme | 20 | €26 → €91 | €56–60 | media ~€100 | **Sopra** la fascia |

Lettura: **i prezzi di lancio sono al limite alto per ogni tipo di locale**, e
questo prima ancora di avere utenti. Ma il prezzo non è il motivo principale
del no: 11 su 20 dicono "fiducia" (nessun utente) e solo 3 "prezzo".

### 2. Cosa fa il mercato

Nessun concorrente trovato vende abbonamenti mensili di visibilità ai locali. I
ticketing (Xceed, DICE, Eventbrite) guadagnano con **commissioni sui
biglietti**; Instagram e Facebook sono gratis. Il canone è una categoria nuova:
va introdotto quando c'è un pubblico da mostrare.

### 3. Cosa serve all'azienda

Il CFO: ogni locale pagante lascia quasi tutto il canone (contributo ~97%), i
costi fissi sono ~€484/mese. **A €100 medi bastano 5 locali paganti per il
pareggio; a €63 medi ne servono 8** (vedi `cfo.md`). Il prezzo quindi non deve
essere alto per stare in piedi: deve essere facile da accettare.

### 4. La raccomandazione

| Piano | Per chi | Prezzo | Cosa include |
| --- | --- | --- | --- |
| **Gratis** | Tutti i locali | €0, per sempre | Profilo, tutte le serate su mappa e calendario, caricamento fatto da Aroundly |
| **Pro** | Bar e locali con DJ set | **€39/mese** | Serate in evidenza, badge "Consigliato", notifica alla zona, statistiche per serata |
| **Club** | Discoteche e locali grandi | **€119/mese** | In cima alla home nelle tue serate, notifiche di zona, statistiche avanzate, report mensile |
| **Biglietti** | Chi vende ingressi | €0,50 a biglietto, a carico di chi compra | Nessun canone |

- **Mese per mese, nessun vincolo minimo.** Il vincolo di 3 mesi è citato da
  quasi tutti come motivo di no.
- **I piani a pagamento si attivano solo quando la città supera 2.000 utenti
  attivi al mese**, numero pubblicato. Prima, tutto gratis.
- €39 sta dentro la fascia dei bar (sotto il tetto di €60) e nella parte bassa
  di quella dei locali con DJ; €119 sta sotto la soglia "caro" delle discoteche.

### 5. L'offerta di apertura

**Founding partner**: chi entra prima della soglia dei 2.000 utenti tiene Pro a
€39 e Club a €119 per 12 mesi. Non è uno sconto finto: sono i prezzi reali, e
dopo 12 mesi possono salire. Niente prezzi "barrati" che non sono mai stati
applicati: i listini €80/€220/€400 della proposta v4 non vanno più mostrati
come prezzo di confronto.

### 6. Cosa testare con locali veri

- **Pro a €29 contro €39** nella stessa città: metà dei locali riceve un'offerta,
  metà l'altra, alla prima soglia di utenti. Si misura quanti attivano.
- **Club a €99 contro €149** con le prime 6–8 discoteche.
- **Commissione biglietti €0,50 contro €1,00**: verificare prima le commissioni
  reali di Xceed e DICE nella zona chiedendo ai locali.

### 7. Le obiezioni sul prezzo (parole del panel)

- "Fifty euro a month plus VAT for three months minimum is real money on my
  margins, and I don't know if anyone in my town will open an app that isn't
  even public yet." (P006)
- "A monthly fee with a 3-month minimum is too much for a bar like mine." (P008)
- "I clear 28 grand a year and every monthly fee gets cut unless it fills the
  room." (P012)

Sono acquirenti simulati: servono a scegliere cosa testare, non sono prove.

### 8. Ritest con l'offerta nuova (panel v2, stessi 20 proprietari)

Con l'inserimento gratuito e i piani Pro €39 / Club €119 attivi solo dopo
2.000 utenti, la fascia accettabile per il canone mensile diventa **€12 → €60**,
con il prezzo "equo" (IPP) a **€25** (`panel-v2/pricing-curve.md`). €39 è
dentro la fascia ma sopra il punto di equilibrio: **il test Pro €29 contro €39
diventa la prima cosa da provare** quando la città arriva alla soglia.

## The offer

Metodo: la prospettiva Offerta del board (sintesi del framework di *$100M
Offers*; non sono parole dell'autore). Materia prima: i no del panel
(`panel/results.md`), le lamentele sui concorrenti, le condizioni del board.

### 1. I problemi del proprietario (con le sue parole, dal panel)

Prima di comprare
1. "How many people actually use this app here?" (quasi tutti)
2. "An app nobody has installed yet" — paga per un pubblico che non c'è
3. "I'm not signing a 3-month minimum with a startup"
4. "Will you still be around in six months?"
5. "Instagram does the job for free"
6. "My PR guys and the WhatsApp lists fill the room"
7. "Fifty euro a month plus VAT is real money on my margins"
8. "My competitors will be on it too, so what do I gain?"
9. "I've paid for a promo platform that brought nobody"

Durante
10. "I don't have time to manage another platform"
11. Caricare le serate è un lavoro in più
12. Non sa usare dashboard e statistiche
13. Il socio o il commercialista devono approvare

Dopo
14. "Views don't mean people at the door"
15. Non sa se la spesa si ripaga
16. Il feed pieno di sponsorizzati non lo distingue dagli altri
17. Paura di restare legato se l'app non cresce

### 2. Soluzioni, valutate e tagliate

| Problema | Soluzione | Valore (1–5) | Costo (1–5) | Tenuta? |
| --- | --- | ---: | ---: | --- |
| 1, 2, 9 | Paghi solo dopo 2.000 utenti attivi in città, numero pubblicato | 5 | 1 | ✅ |
| 3, 17 | Mese per mese, nessun vincolo | 5 | 2 | ✅ |
| 10, 11 | Carichiamo noi le locandine da Instagram | 5 | 3 (tempo soci) | ✅ |
| 14, 15 | Garanzia: sotto 500 visualizzazioni nel mese, il mese è gratis | 4 | 2 | ✅ |
| 5 | Inserimento gratuito per sempre | 4 | 1 | ✅ |
| 7 | Pro a €39 (test €29) invece di €50–150 | 4 | 2 | ✅ |
| 6 | Biglietti in app a €0,50 a carico di chi compra | 3 | 2 | ✅ |
| 4 | Prezzo founding partner bloccato 12 mesi | 3 | 2 | ✅ |
| 8 | Esclusiva territoriale | 3 | 5 (uccide la rete) | ❌ |
| 12 | Report PDF mensile per tutti | 2 | 3 | ❌ solo Club |
| — | Trailer video, 4 badge, mappa "avanzata" | 2 | 3 | ❌ rimandati |

### 3. L'offerta: "Founding Partner Aroundly"

- **Il cuore:** *Tutte le tue serate davanti a chi sta decidendo dove uscire
  stasera, senza che tu muova un dito.*
- **Bonus 1, "Ci pensiamo noi":** carichiamo noi ogni locandina da Instagram.
  Uccide "non ho tempo".
- **Bonus 2, "Il numero è pubblico":** la soglia di 2.000 utenti attivi al mese e
  il conteggio aggiornato sono visibili a tutti. Uccide "nessuno la usa".
- **Bonus 3, "Prezzo bloccato":** chi entra prima della soglia tiene Pro €39 e
  Club €119 per 12 mesi.
- **Garanzia:** se in un mese pagato le tue serate fanno meno di 500
  visualizzazioni, quel mese non lo paghi. *Costo:* se il 20% dei locali Pro la
  attiva, si perdono ~€8 per locale al mese in media: il contributo scende da
  €60,80 a ~€53. Sostenibile.
- **Urgenza vera:** il prezzo founding partner vale solo prima della soglia dei
  2.000 utenti. Nessun conto alla rovescia finto.
- **Nome:** "Founding Partner Aroundly".

### 4. Equazione del valore (1–10), prima e dopo

| Elemento | v1 | v2 | Cosa lo sposta |
| --- | ---: | ---: | --- |
| Risultato sognato (più gente alla porta) | 6 | 6 | Invariato: l'app è la stessa |
| Probabilità percepita di ottenerlo | 2 | 5 | Soglia utenti pubblica, garanzia |
| Tempo per il risultato | 3 | 4 | Inserimento immediato e gratuito |
| Fatica e sacrificio | 3 | 9 | Gratis, niente vincolo, carichiamo noi |

### 5. Ritest sul panel (stessi 20 proprietari, seed 7)

| | v1 (offerta attuale) | v2 (Founding Partner) |
| --- | ---: | ---: |
| Pagherebbero subito | 1 su 20 (5%) | 1 su 20 (5%)* |
| Accettano l'inserimento gratuito (nelle loro parole) | — (non offerto) | **19 su 20** |
| Motivo principale del no | fiducia 11, prezzo 3 | fiducia 7, abitudine 6, prezzo 1 |
| Fascia di prezzo accettabile | €26–91 | €12–60 |

\* Nella v2 nessuno può pagare prima della soglia: il "sì" è all'inserimento
gratuito. Il risultato utile è un altro: **le obiezioni "vincolo" e "prezzo"
quasi spariscono** e resta una sola domanda, "ci sono utenti?". Quella non la
risolve un'offerta: la risolve il lancio verso gli utenti. Il panel conferma il
board: il problema è il mercato a due lati, non il prezzo.

Sono acquirenti simulati: tendono a essere accomodanti, quindi i numeri sono un
massimo. Va confermato con locali veri (vedi `launch.md`).

## The numbers

Tutte le cifre sono in **euro, IVA esclusa** (il tool stampa "$"). Unità: **un
locale pagante per un mese**. Fonti e stime in `cfo-sources.md`. Quasi tutti i
costi sono **stime**: vanno sostituiti con preventivi veri.

**Due scenari a confronto**

| | v1: offerta attuale (€50/150/250, vincolo 3 mesi) | v2: gratis prima, Pro €39 / Club €119 dopo 2.000 utenti |
| --- | ---: | ---: |
| Prezzo medio per locale | €100 | €63 |
| Contributo per locale (prezzo meno costi variabili) | €97,25 | €60,80 |
| Costi fissi al mese | €484 | €634 (più marketing utenti) |
| **Pareggio** | **5 locali paganti** | **11 locali paganti** |
| Locali paganti a fine anno 1 (ipotesi) | 35 | 22 |
| **Risultato anno 1** | **+€9.655** | **−€2.440** |
| Cassa necessaria prima di stare in piedi | €4.326 | €6.951 |
| File | `cfo-v1.md` | `cfo.md` |

- **Il margine:** il servizio quasi non ha costi per locale, quindi ogni euro
  di canone è margine. Il problema non è il margine, sono **i locali paganti**.
- **La riga da guardare: la rampa.** La v1 è in utile solo perché ipotizza
  locali paganti dal mese 3. Il panel simulato dice 1 su 20 (5%) con l'offerta
  attuale: per avere 35 paganti servirebbero ~700 locali visitati. **Lo scenario
  v1 non è credibile; la v2 è più lenta ma onesta.** Con la v2, a −20% di
  volume il risultato peggiora di ~€1.000 (−€3.474).
- **Cassa:** servono circa **€7.000** prima che Aroundly si ripaghi (v2),
  compresi ~€3.000 di spese iniziali stimate (società, GDPR, store, lancio).
  Divisi per tre soci, circa €2.300 a testa, oltre al tempo non pagato.
- **Tre modi per migliorare il risultato (dalla v2):**
  1. **Prezzo medio:** a €70 invece di €63 il pareggio scende a ~10 locali;
     a €56 (Pro a €29) sale a 12 e l'anno 1 peggiora di ~€600 (verificato col
     tool: −€3.035).
  2. **Commissione biglietti** (€0,50): non è nei conti. Con 2.000 biglietti al
     mese in città sarebbero +€1.000 al mese, più di tutti i costi fissi. È
     l'entrata da verificare per prima.
  3. **Costi fissi:** il marketing utenti (€450) è la voce più grande; riempire
     il calendario a mano e usare contenuti organici lo riduce.
- **Condizioni del board sui soldi:** soglia utenti prima di far pagare →
  rispettata nella v2. Commissione sui biglietti → fissata come proposta
  (€0,50), da validare. Prova di conversione pagante → ancora da fare con locali
  veri.

Non è consulenza finanziaria o fiscale: forma societaria (SRL o altro), IVA e
contributi vanno verificati con un commercialista prima di muovere soldi.

---

## Unit economics: Aroundly, modello v2: gratis per i locali, Pro 39 / Club 119 dopo 2.000 utenti attivi

Every number below comes from the input file. Nothing is looked up or guessed.

### One locale pagante al mese

| line | per locale pagante al mese |
| --- | ---: |
| Price | $63.00 |
| Commissione carta Stripe (1,5% + 0,25 EUR, stima) | -$1.20 |
| Infrastruttura per locale (stima) | -$1.00 |
| **Contribution** (what each locale pagante al mese leaves to pay the fixed costs) | **$60.80** (97%) |

### The margin that matters

Fixed costs: $634 a month (Firebase Blaze (stima a basso traffico) $25, Netlify Pro (20 USD) $19, Apple Developer (99 EUR/anno) + dominio $10, Commercialista (stima) $80, Marketing verso gli utenti in una citta (stima) $450, Materiali stampati, telefono, strumenti (stima) $50).

- **Break-even: 11 locale pagante al meses a day.** Below that you lose money every month.
- **Profit margin at your plan** (40 a day): **71%** of every sale, after every cost.
- Capacity: 150 a day.

### Year 1, month by month

| month | locale pagante al meses a day | revenue | profit | cumulative (after $2,973 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 0 | $0 | -$634 | -$3,607 |
| 2 | 0 | $0 | -$634 | -$4,241 |
| 3 | 0 | $0 | -$634 | -$4,875 |
| 4 | 0 | $0 | -$634 | -$5,509 |
| 5 | 0 | $0 | -$634 | -$6,143 |
| 6 | 3 | $189 | -$452 | -$6,595 |
| 7 | 6 | $378 | -$269 | -$6,864 |
| 8 | 9 | $567 | -$87 | -$6,951 |
| 9 | 12 | $756 | $96 | -$6,855 |
| 10 | 15 | $945 | $278 | -$6,577 |
| 11 | 18 | $1,134 | $460 | -$6,117 |
| 12 | 22 | $1,386 | $704 | -$5,413 |

- **Year 1 operating profit: -$2,440** on $5,355 of revenue.
- After the $2,973 startup spend: -$5,413.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$6,951**.

### What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 71% | 11 | -$2,440 |
| Price -10% | 68% | 12 | -$2,976 |
| Volume -20% | 65% | 11 | -$3,474 |
| Unit costs +15% | 71% | 11 | -$2,468 |

### Red flags

- Year 1 loses money on operations (-$2,440).
- The startup spend is not earned back within year 1.

## Marketing

Aroundly ha **due pubblici** e due campagne: i **locali** (gratis, si
convincono a voce) e gli **utenti** (18–35 anni che escono; il vero lavoro del
lancio). Il board e il panel dicono la stessa cosa: senza utenti nessun locale
paga. **Una sola città.** Consigliata **Padova** (grande popolazione
universitaria, tanti locali, presenza di DICE e Zero.eu = scena attiva);
alternativa **Udine** se i soci vivono lì e conoscono i locali. La scelta va
fatta dai soci in base a dove hanno contatti.

### 1. Posizionamento

Per gli **utenti**:
1. *Per chi esce a Padova e non sa dove andare stasera, Aroundly è l'unica app
   con tutte le serate della città in un posto solo, anche quelle gratis e dei
   bar, a differenza di Instagram dove le trovi solo se segui già il locale.*
   ← **consigliata**: risponde al "buco" trovato in `competitors.md`.
2. *Stasera, vicino a te.* (versione corta della 1)
3. *La guida della notte di Padova, aggiornata ogni giorno.*

Per i **locali**:
- *Instagram parla a chi ti segue già. Aroundly ti fa trovare da chi sta
  decidendo dove uscire stasera. Gratis finché non ti portiamo pubblico.*
  Evidenza: il panel cita "Instagram works for free" come seconda obiezione; la
  risposta è non competere sul prezzo, ma sul pubblico nuovo.

### 2. Canali

| Canale | Perché | Costo | Come capire se funziona |
| --- | --- | --- | --- |
| ✅ **Instagram/TikTok di Aroundly**: "Stasera a Padova" ogni giovedì–sabato alle 18 | Il pubblico vive lì; contenuto utile gratis | €0–150/mese di sponsorizzate | Clic al link, installazioni da UTM |
| ✅ **Ambassador universitari** (5–10 studenti, associazioni, ESN Padova) | Gli studenti sono il pubblico più denso | Ingressi omaggio dai locali partner, €0 cassa | Codici invito per ambassador |
| ✅ **QR nei locali partner** (adesivo al bancone, nei bagni, sui tavoli) | Chi è già fuori è il pubblico perfetto | ~€100 di stampa | Scansioni per locale |
| Volantinaggio in università | Utile al lancio | €50 | Codice dedicato |
| ❌ Google Ads | Nessuno cerca "app serate" | — | — |
| ❌ Influencer a pagamento | Budget troppo piccolo | — | — |

### 3. Campagna 30 giorni (lancio utenti giovedì 3 dicembre 2026)

| Data | Canale | Cosa |
| --- | --- | --- |
| gio 19 nov | Instagram | Prima "Stasera a Padova" (lista manuale di 10 serate) |
| ven 20 – sab 21 nov | Instagram, storie | Le serate del weekend, link alla lista d'attesa |
| lun 23 nov | Ambassador | Briefing e codici invito |
| gio 26 nov | Instagram + TikTok | Video "Abbiamo messo tutte le serate di Padova in un'app" |
| ven 27 – sab 28 nov | QR nei locali | Adesivi nei primi locali partner |
| lun 30 nov | Università | Volantini, codice ambassador |
| mer 2 dic | Tutti | "Domani si apre" |
| **gio 3 dic** | **Tutti** | **Lancio pubblico** + serata di lancio in un locale partner |
| 4–5 dic | Storie | "Stasera" con link diretto all'app |
| 10, 17 dic | Instagram | "I 5 eventi del weekend" (salvabili) |
| 18–31 dic | Tutti | Speciale feste e Capodanno: tutte le serate in un posto |
| ogni gio–sab | Instagram | "Stasera a Padova" (contenuto fisso quando non c'è niente di nuovo) |

### 4. Dieci hook

Ognuno risponde a un dubbio emerso (per gli utenti) o a un'obiezione del panel
(per i locali).

Utenti:
1. "Tutte le serate di Padova stasera. Una sola app." (dispersione)
2. "Non devi seguire 40 locali su Instagram." (dispersione)
3. "Stasera gratis a Padova: 7 serate." (prezzo per lo studente)
4. "Dove si balla stasera a 10 minuti da te?" (vicinanza)
5. "Il calendario del weekend, prima che lo scopri dalle storie." (tempismo)
6. "Salva la serata, mandala nel gruppo." (decidere con gli amici)

Locali:
7. "Gratis. Le locandine le carichiamo noi." (P014: "no time")
8. "Paghi solo quando ti portiamo pubblico: il numero è pubblico." (P001: "how many people")
9. "Nessun vincolo. Mese per mese." (P008: "3-month minimum")
10. "Se il mese non funziona, non lo paghi." (P002: "brought nobody")

### 5. Budget e numeri

- **Budget:** €450/mese (dentro il budget dei soci): €150 sponsorizzate, €100
  stampa QR e volantini, €200 serata di lancio e premi ambassador.
- **Quanto si può spendere per un locale pagante:** un locale Pro lascia ~€61 al
  mese (CFO). Se resta 6 mesi vale ~€365: si possono spendere fino a ~€120 per
  conquistarlo (un terzo del valore). Per un utente, oggi, il valore non è
  misurabile: si spende per arrivare alla soglia di 2.000.
- **Tre numeri da guardare ogni settimana:**
  1. **Utenti attivi settimanali** a Padova (obiettivo: 2.000 attivi al mese
     entro fine febbraio 2027). Allarme: meno di 300 a fine dicembre.
  2. **Copertura del calendario**: % delle serate reali della città presenti
     in app (obiettivo ≥ 80% ogni weekend). Allarme: sotto 60%.
  3. **Salvataggi + condivisioni per serata** (il segnale che interessa ai
     locali). Allarme: sotto 5 per serata in media dopo un mese.

Niente recensioni, numeri o testimonianze inventate; le citazioni del panel non
vanno mai usate in pubblicità. Le sponsorizzate vanno segnalate come tali.

## Brand

Il nome Aroundly esiste già ed è usato su dominio, Instagram e materiali.
Questa skill quindi **non ricomincia da zero**: verifica i rischi del nome,
propone alternative di riserva e definisce voce e aspetto.

### 1. Il nome: rischi trovati

Ricerca pubblica del 26/10/2026:
- ⚠️ **Un'altra "Aroundly" in Italia:** app-guida per turisti a Palermo,
  lanciata da iInformatica Srls nel 2017 ([Balarm](https://www.balarm.it/news/magazine/aroundly-un-app-guida-i-turisti-alla-scoperta-della-citta-di-palermo-18761)).
  Stato attuale non noto.
- ⚠️ **aroundly.com** è stato un'app di foto geolocalizzate (circa 2010)
  ([Presse-Citron](https://www.presse-citron.net/aroundly/), [iPhoneItalia](https://www.iphoneitalia.com/?p=306446)).
- Nomi simili: AroundMe, AroundYou, AroundUs (app di ricerca locale).
- **Instagram:** l'handle è passato da `aroundly.app` ad `aroundlyy`
  (email del 27/09/2026). La doppia "y" è debole: difficile da dire a voce.

**Controlli da fare subito (li possono fare solo i soci):**
- **Marchio:** cercare "Aroundly" su [UIBM](https://uibm.mise.gov.it) (Italia),
  [EUIPO eSearch](https://euipo.europa.eu/eSearch/) e
  [TMview](https://www.tmdn.org/tmview/) nelle **classi 9** (app), **35**
  (pubblicità e promozione), **41** (organizzazione di eventi, intrattenimento)
  e **42** (software come servizio). Se iInformatica o altri l'hanno
  registrato in classe 9, serve un avvocato prima di investire nel brand.
- **Dominio:** aroundly.app è vostro; controllare se aroundly.it è libero.
- **Handle:** provare a recuperare `aroundly` o `aroundly.app` su Instagram,
  `@aroundly` su TikTok.

Questa è solo una ricerca pubblica: un consulente marchi conferma, e niente è
registrato finché non lo registrate voi.

**Nomi di riserva** (se il marchio è bloccato): **Stasera** (descrittivo, forte
in italiano, probabilmente non registrabile da solo), **Notturno**, **Fuori**,
**Giro**, **Aroundly Night**. Da verificare con gli stessi controlli.

### 2. Promessa, tagline, voce

- **Promessa:** *Se stasera succede qualcosa vicino a te, è su Aroundly.*
- **Tagline (tre opzioni):** "Stasera, vicino a te." · "Tutta la notte della
  tua città." · "Esci meglio."
- **Voce:**

| Aggettivo | Sì | No |
| --- | --- | --- |
| **Diretta** | "Stasera a Padova: 12 serate." | "Scopri un universo di esperienze notturne!" |
| **Complice** | Parla come un amico che sa dove si va | Tono da ente del turismo |
| **Onesta** | "Siamo nuovi, aiutaci a riempirla." | "La app n.1 della nightlife" |

Prima/dopo di una riga del pitch:
- Prima: "La nightlife della tua città, tutta qui."
- Dopo: "Tutte le serate di stasera a Padova. Anche quelle gratis."

### 3. L'aspetto (brief)

- **Colori:**
  - Notte `#0E0B1F` (fondo, il "buio" della sera)
  - Neon `#C6F432` (azione, "stasera"; testo nero su neon: contrasto ~16:1)
  - Rosa `#FF4F9A` (badge "In evidenza"/sponsorizzato; testo bianco su rosa
    va verificato, usare testo Notte su rosa per AA)
  - Testo bianco su Notte: contrasto ~19:1 (AA ok).
- **Caratteri:** display **Space Grotesk**, testo **Inter**: entrambi gratuiti
  (SIL Open Font License) su Google Fonts.
- **Logo:** deve funzionare come icona a 32px e su un adesivo QR al bancone.
  Una "A" che è anche un segnaposto della mappa. Niente palle da discoteca o
  bicchieri (cliché).
- **I primi cinque punti di contatto:**
  1. L'adesivo QR nel locale: "Stasera qui. E in altri 30 posti a Padova."
  2. La schermata di apertura: le serate di stasera, non un login.
  3. La conferma del biglietto: QR grande, ora e indirizzo.
  4. Il primo post: "Abbiamo messo tutte le serate di Padova in un posto."
  5. La risposta al primo reclamo (serata cancellata): entro un'ora, scuse
     e correzione visibile in app.

**Sponsorizzati:** ogni serata in evidenza a pagamento porta l'etichetta
"In evidenza" (condizione del board). Il rosa è riservato a questo.

## Operations

Aroundly non ha magazzino né turni di cassa: le operazioni sono **tenere
completo e corretto il calendario**, **far funzionare l'app** e **seguire i
locali**. Tre soci, nessun dipendente.

### 1. Il ciclo di ogni giorno (◆ = lo vede l'utente)

1. Mattina: controllare Instagram e i canali dei locali della città per nuove
   locandine e cambi (DJ, orari, serate annullate).
2. Caricare o correggere le serate in app ◆ (obiettivo: ≥ 80% delle serate
   reali della città).
3. Pomeriggio: post "Stasera a Padova" ◆ (giovedì–sabato).
4. Rispondere a locali e utenti ◆ (entro 2 ore in orario serale).
5. Sera: controllo a campione che le serate di stasera siano giuste ◆.
6. Lunedì: statistiche della settimana ai locali (quando c'è la dashboard) ◆.

### 2. Fornitori e strumenti

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

### 3. Persone: chi fa cosa

| Socio | Ruolo | Ore/settimana (stima) |
| --- | --- | --- |
| Socio A | **Prodotto e tecnica**: backend, app, sicurezza, dati | 15–20 |
| Socio B | **Locali**: visite, inserimenti, rapporti, contratti | 10–15 |
| Socio C | **Utenti e contenuti**: calendario, social, ambassador | 10–15 |

Nessuno stipendio previsto: il tempo dei soci non è nei costi del CFO. Se in
futuro si pagano compensi, contributi e forma vanno chiariti col commercialista.
I nomi vanno assegnati dai soci.

### 4. Procedure (SOP)

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

### 5. Licenze, permessi, obblighi (da confermare)

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

### 6. Registro dei rischi

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

## Launch plan

Città: **Padova** (consigliata; i soci possono sostituirla con Udine o un'altra
città dove hanno più contatti: le date restano valide). Oggi è lunedì 26
ottobre 2026.

### 1. Il test prima di spendere

Due test, uno per lato del mercato, prima del lancio pubblico:

| Test | Come | Dal / al | Successo se |
| --- | --- | --- | --- |
| **Locali** | Proporre l'inserimento gratuito "Founding Partner" a 50 locali di Padova | 2 – 22 nov | **≥ 30 dicono sì** (60%). Il panel simulato dice ~95%: se i locali veri sono molto meno, fidarsi di loro |
| **Utenti** | Pagina "Stasera a Padova" su Instagram + lista d'attesa sul sito | 2 – 29 nov | **≥ 500 iscritti** alla lista d'attesa |

Se un test fallisce: tornare a `/founder-offer` (locali) o `/founder-marketing`
(utenti) prima di lanciare.

Il test dei pagamenti arriva più tardi: quando la città supera 2.000 utenti
attivi al mese, proporre Pro a €29 a metà dei locali e a €39 all'altra metà
(`pricing.md`). **Successo: ≥ 8 locali paganti nel primo mese di piani attivi.**

### 2. Il conto alla rovescia

Il **percorso critico** (se slitta, slitta il lancio) è in grassetto.

| Settimana | Attività | Chi | Entro |
| --- | --- | --- | --- |
| 26 ott – 1 nov | **Regole di sicurezza Firebase, database in UE, test completo dell'app** | Socio A | **1 nov** |
| | Ricerca marchio UIBM/EUIPO; decidere l'handle Instagram | Socio C | 1 nov |
| | Sistemare l'email di benvenuto (`[Company Name]`) | Socio A | 1 nov |
| 2 – 8 nov | Elenco di tutti i locali della città (target 80–120) | Socio B | 8 nov |
| | Avvio pagina "Stasera a Padova" e lista d'attesa | Socio C | 2 nov |
| | Commercialista: forma societaria, partita IVA, privacy | Tutti | 8 nov |
| 9 – 22 nov | **Visite ai locali: 50 proposte, consensi scritti** | Socio B | **22 nov** |
| | **Caricare le serate di tutti i locali, anche non partner, da fonti pubbliche** | Socio C | continuo |
| | App sugli store (revisione Apple: prevedere 1–2 settimane) | Socio A | **20 nov** |
| 23 – 29 nov | Ambassador universitari, adesivi QR nei locali partner | Socio C | 28 nov |
| | Prova con amici: 30 persone usano l'app per un weekend | Tutti | 29 nov |
| 30 nov – 2 dic | Correzioni dalla prova, materiali di lancio | Tutti | 2 dic |
| **gio 3 dic** | **Lancio pubblico** + serata in un locale partner | Tutti | 3 dic |

Niente biglietti in app al lancio: prima va chiarito l'aspetto fiscale
(`ops.md`).

### 3. Giorno di lancio (giovedì 3 dicembre)

| Ora | Cosa | Chi |
| --- | --- | --- |
| 10:00 | Controllo finale: app sugli store, serate di stasera e del weekend complete | A, C |
| 12:00 | Post e storie "Aroundly è online", messaggio alla lista d'attesa | C |
| 13:00 | Ambassador: messaggi nei gruppi universitari con codice invito | C |
| 15:00 | Giro dei locali partner: adesivo QR presente, ringraziamento | B |
| 18:00 | "Stasera a Padova" con link all'app | C |
| 21:00 | Serata di lancio nel locale partner: QR all'ingresso | Tutti |
| 23:00 | Controllo: installazioni, errori, recensioni; risposta a ogni problema | A |

Se si blocca qualcosa: app ferma → messaggio onesto sui social e correzione
(rischio 1 in `ops.md`); serata sbagliata in app → correzione entro 30 minuti.

### 4. I primi 30 giorni

| Numero (ogni lunedì) | Obiettivo a 30 giorni | Allarme → cosa cambiare |
| --- | --- | --- |
| Utenti attivi al mese | 800–1.000 (verso 2.000 a fine febbraio) | < 300 a fine dicembre → cambiare canali o città |
| Copertura del calendario nei weekend | ≥ 80% | < 60% → più tempo al caricamento, chiedere ai locali |
| Salvataggi + condivisioni per serata | ≥ 5 | < 2 → il problema è l'app, non il marketing |
| Locali con inserimento gratuito | ≥ 40 | < 25 → rivedere il discorso ai locali |
| Costi del mese | ≤ €650 | > €800 → tagliare sponsorizzate |

**Revisioni:**
- **Giorno 7 (10 dic):** chi ha installato è tornato il weekend? Quali serate
  hanno più salvataggi?
- **Giorno 14 (17 dic):** il calendario è davvero completo? Cosa manca e perché?
- **Giorno 30 (2 gen 2027):** si raggiungono 2.000 attivi entro febbraio con
  questo ritmo? Se no: cambiare i canali, non la città, per un altro mese; poi
  decidere.

_The panel is simulated buyers and the numbers are projections from your inputs. Confirm demand with real customers and costs with real quotes before you spend. Not financial, legal or tax advice._
