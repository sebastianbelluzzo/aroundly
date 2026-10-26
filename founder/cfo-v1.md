# Unit economics: Aroundly (Friuli Venezia Giulia e Veneto)

Every number below comes from the input file. Nothing is looked up or guessed.

## One locale pagante al mese

| line | per locale pagante al mese |
| --- | ---: |
| Price | $100.00 |
| Commissione carta Stripe (1,5% + 0,25 EUR, stima) | -$1.75 |
| Infrastruttura per locale (Firebase/Netlify, stima) | -$1.00 |
| **Contribution** (what each locale pagante al mese leaves to pay the fixed costs) | **$97.25** (97%) |

## The margin that matters

Fixed costs: $484 a month (Firebase Blaze (stima a basso traffico) $25, Netlify Pro (20 USD) $19, Apple Developer (99 EUR/anno) + dominio $10, Commercialista (stima) $80, Marketing verso gli utenti (stima) $300, Materiali stampati, telefono, strumenti (stima) $50).

- **Break-even: 5 locale pagante al meses a day.** Below that you lose money every month.
- **Profit margin at your plan** (40 a day): **85%** of every sale, after every cost.
- Capacity: 150 a day.

## Year 1, month by month

| month | locale pagante al meses a day | revenue | profit | cumulative (after $2,973 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 0 | $0 | -$484 | -$3,457 |
| 2 | 0 | $0 | -$484 | -$3,941 |
| 3 | 2 | $200 | -$290 | -$4,230 |
| 4 | 4 | $400 | -$95 | -$4,326 |
| 5 | 6 | $600 | $100 | -$4,226 |
| 6 | 9 | $900 | $391 | -$3,835 |
| 7 | 12 | $1,200 | $683 | -$3,152 |
| 8 | 16 | $1,600 | $1,072 | -$2,080 |
| 9 | 20 | $2,000 | $1,461 | -$619 |
| 10 | 25 | $2,500 | $1,947 | $1,328 |
| 11 | 30 | $3,000 | $2,434 | $3,762 |
| 12 | 35 | $3,500 | $2,920 | $6,682 |

- **Year 1 operating profit: $9,655** on $15,900 of revenue.
- After the $2,973 startup spend: $6,682.
- Startup money earned back: month 10.
- Cash you need before it pays for itself: **$4,326**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 85% | 5 | $9,655 |
| Price -10% | 84% | 6 | $8,065 |
| Volume -20% | 82% | 5 | $6,562 |
| Unit costs +15% | 85% | 5 | $9,589 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a real quote.
