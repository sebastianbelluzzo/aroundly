# Aroundly

## Skill installate: Founder skill pack

In questo progetto sono installate le 11 skill di
[Founder skill](https://github.com/Jakeschincariol/founder-skill) di Jake
Schincariol (licenza MIT, versione 1.0, commit `fd9385b`). Servono a mettere
alla prova un'idea di business prima di lanciarla.

Si trovano in `.claude/skills/` e in Claude Code si usano come comandi:
`/founder-board`, `/founder-cfo` e così via. La licenza originale è in
`.claude/skills/FOUNDER-SKILL-LICENSE`.

### Le 11 skill

| comando | ruolo | cosa fa |
| --- | --- | --- |
| `/founder-board` | Consiglio di amministrazione | Tre membri (prospettiva Offerta, Monopolio, Prodotto) valutano l'idea, indicano i rischi e votano. |
| `/founder-competitors` | Analisi concorrenti | Mappa concorrenti diretti, indiretti e alternative, con prezzi e lamentele dei clienti, tutto con link. |
| `/founder-consumer` | Panel di consumatori | Simula 100 acquirenti (20 con `--quick`) e conta chi compra, chi no e perché. |
| `/founder-pricing` | Strategia di prezzo | Calcola la fascia di prezzo accettabile (Van Westendorp) e la confronta con concorrenti e margini. |
| `/founder-offer` | Costruzione dell'offerta | Bonus, garanzia, urgenza reale e nome dell'offerta, poi la ritesta sul panel. |
| `/founder-cfo` | Direttore finanziario | Margini reali, punto di pareggio, primo anno mese per mese, cassa necessaria, rientro dell'investimento. |
| `/founder-marketing` | Direttore marketing | Posizionamento, canali, campagna di lancio di 30 giorni, dieci hook, budget. |
| `/founder-brand` | Brand designer | Nomi (con verifiche di marchio, dominio e social), tono di voce, promessa, brief visivo. |
| `/founder-ops` | Operazioni | Fornitori, personale, routine del primo giorno, strumenti, permessi, registro dei rischi. |
| `/founder-launch` | Lancio | Un test reale economico, il conto alla rovescia, la scaletta del giorno del lancio, i primi 30 giorni. |
| `/founder-plan` | Business plan | Unisce tutto in un business plan con un verdetto calcolato: Profitable, Not yet o Incomplete. |

### Come usarle

Si eseguono in quest'ordine. Ognuna salva il suo lavoro nella cartella
`founder/` del progetto e la successiva lo legge:

```
board -> competitors -> consumer -> pricing -> offer -> cfo -> marketing -> brand -> ops -> launch -> plan
```

Si può anche usarne una sola. Per esempio `/founder-consumer --quick` è un modo
rapido per capire se un'idea merita di essere approfondita.

Gli strumenti Python richiedono Python 3.8 o successivo e non hanno dipendenze
da installare.

### Avvertenze

- Il "consiglio" applica framework pubblicati (*$100M Offers*, *Zero to One*, la
  biografia di Steve Jobs). Non sono quelle persone e non le rappresentano.
- Il panel di consumatori è simulato: serve a trovare obiezioni, non è una
  previsione. Il tasso di acquisto va letto come un massimo, e le decisioni
  importanti vanno confermate con persone reali.
- I numeri valgono quanto i dati inseriti. Non è consulenza finanziaria, legale o
  fiscale.

## Cosa è stato fatto

1. Il pacchetto è stato scaricato da GitHub e il codice controllato prima di
   aggiungerlo: i quattro script Python usano solo la libreria standard, non
   accedono alla rete e non eseguono comandi di sistema.
2. Le 11 cartelle `founder-*` sono state copiate in `.claude/skills/`.
3. È stato aggiunto un `.gitignore` per escludere i file di cache di Python.
4. Questo README riassume il lavoro.

I test inclusi nel pacchetto originale non sono stati eseguiti in questa
sessione.
