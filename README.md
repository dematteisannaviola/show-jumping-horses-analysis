# 🏇 Show Jumping Horses — Nationality Analysis

## 📌 Obiettivo
Analizzare la nazionalità dei cavalli vincenti nel salto ostacoli 
per capire quali paesi dominano la produzione di cavalli d'élite 
e se esiste un divario tra paesi produttori di cavalli e paesi produttori di cavalieri.

## 📊 Dataset
- **FEI Jumping Combination Rankings** (April 2026) — top 200 combinazioni mondiali
- **Paris 2024 Olympics** — risultati individuali salto ostacoli
- **WBFSH World Ranking List 2024** — top 50 stalloni per performance breeding

## 🛠️ Strumenti
- Microsoft Excel / Google Sheets (Pivot Table, grafici)

## 🔍 Domande chiave
1. Quali paesi producono più stalloni vincenti?
2. Quali nazionalità dominano le Olimpiadi?
3. Quali paesi hanno più cavalieri nel ranking FEI mondiale?
4. C'è un divario tra paesi produttori di cavalli e paesi produttori di cavalieri?

## 💡 Key Findings
- 🇩🇪 La **Germania** produce il 34% degli stalloni top mondiali (17/50 WBFSH)
- 🇳🇱 **GER + NED + BEL** coprono l'**80%** dei top 50 stalloni da salto
- 🇺🇸 Gli **USA** guidano il ranking FEI con 31 combinazioni top — pur producendo quasi zero stalloni d'élite
- 🌍 Il mondo anglofono (USA, IRL, GBR) domina i cavalieri ma dipende strutturalmente dai cavalli europei
- 🇳🇱 L'**Olanda** è l'unico paese dove la produzione di cavalli supera quella di cavalieri d'élite
## 📖 Note di Analisi

### Concentrazione della produzione di stalloni
Il mercato internazionale della riproduzione nel salto ostacoli 
è altamente concentrato: Germania, Olanda e Belgio insieme 
producono l'**80% dei top 50 stalloni mondiali**, con la Germania 
che da sola rappresenta il 34% (17/50).

### Qualità vs Quantità — Media punti FEI
Nonostante le grandi differenze nel numero di cavalieri in classifica,
la media dei punti per cavaliere è sorprendentemente simile tra le nazioni (354–433).
Il Regno Unito guida con 433,5 punti medi per cavaliere, il che suggerisce
pochi ma costantemente eccellenti. Questo indica che **la qualità individuale 
dei cavalieri d'élite è omogenea a livello globale** — ciò che differisce 
è la capacità di ogni paese di esprimere volume.

### Indice di dipendenza
Il rapporto tra cavalieri top e stalloni top rivela una divisione strutturale:

| Paese | Indice | Interpretazione |
|---|---|---|
| NED | 0,4 | Esportatore netto — produce più cavalli di quanti ne monta |
| GBR | 1,0 | Autosufficiente |
| BEL | 1,1 | Quasi autosufficiente |
| GER | 1,4 | Lieve dipendenza |
| FRA | 2,7 | Dipendenza significativa da cavalli stranieri |
| IRL | ∞ | Dipendenza totale — zero produzione di stalloni d'élite |
| USA | ∞ | Dipendenza totale — zero produzione di stalloni d'élite |

Il mondo anglofono (USA, IRL, GBR) domina le classifiche dei cavalieri
ma dipende quasi interamente dalla riproduzione dell'Europa continentale.
L'Olanda è l'unico paese in cui la produzione di stalloni d'élite supera il numero di cavalieri top espressi (esporta talento equino nel mondo invece di importarlo).

## 📁 File
- `show_jumping_data.xlsx` — dataset completo con analisi e grafici

## ⚠️ Status
✅ Completato — Maggio 2026
