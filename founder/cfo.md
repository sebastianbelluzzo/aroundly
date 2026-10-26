# CFO: nota in parole semplici

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

# Unit economics: Aroundly, modello v2: gratis per i locali, Pro 39 / Club 119 dopo 2.000 utenti attivi

Every number below comes from the input file. Nothing is looked up or guessed.

## One locale pagante al mese

| line | per locale pagante al mese |
| --- | ---: |
| Price | $63.00 |
| Commissione carta Stripe (1,5% + 0,25 EUR, stima) | -$1.20 |
| Infrastruttura per locale (stima) | -$1.00 |
| **Contribution** (what each locale pagante al mese leaves to pay the fixed costs) | **$60.80** (97%) |

## The margin that matters

Fixed costs: $634 a month (Firebase Blaze (stima a basso traffico) $25, Netlify Pro (20 USD) $19, Apple Developer (99 EUR/anno) + dominio $10, Commercialista (stima) $80, Marketing verso gli utenti in una citta (stima) $450, Materiali stampati, telefono, strumenti (stima) $50).

- **Break-even: 11 locale pagante al meses a day.** Below that you lose money every month.
- **Profit margin at your plan** (40 a day): **71%** of every sale, after every cost.
- Capacity: 150 a day.

## Year 1, month by month

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

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 71% | 11 | -$2,440 |
| Price -10% | 68% | 12 | -$2,976 |
| Volume -20% | 65% | 11 | -$3,474 |
| Unit costs +15% | 71% | 11 | -$2,468 |

## Red flags

- Year 1 loses money on operations (-$2,440).
- The startup spend is not earned back within year 1.
