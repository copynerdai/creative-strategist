# Asset per brand — Starter ×2, Hook, Headline

> Usato dall'orchestratore nella Fase 3. I 4 asset vivono in `<archivio>/<brand>/asset-prompt/` e si costruiscono UNA volta, poi si **aggiornano** a ogni nuovo vincitore o errore ricorrente (mai riscritti da zero: la sezione «Importante» è memoria accumulata).

---

## 1. Starter Prompt — DUE file separati, mai mischiarli

`starter-unaware.md` (bucket unaware/problem-aware) e `starter-solution.md` (bucket solution/product-aware). Strutture e linguaggio dei due bucket sono fondamentalmente diversi: mischiarli confonde gli output.

Struttura (dal corso, adattata):

```
Processa questo e dimmi che hai capito. Queste sono le ads vincenti di [BRAND]
per il bucket [unaware/problem-aware | solution/product-aware]. Le userai come
modelli per creare nuove ads basate sul loro stile, tono, lunghezza e dettagli.
Usale come baseline: non creare ads troppo derivative, ma cattura l'essenza,
la sensazione e i dettagli importanti.

Importante:
[ISTRUZIONI SPECIFICHE — vedi sotto]

[LE ADS VINCENTI DEL BUCKET — copy verbatim dal corpus, con fonte e metriche realmente disponibili]
```

**La sezione «Importante» (il cervello che cresce):**
- Punti di prova ricorrenti del brand (numeri, studi, statistiche che si usano sempre — SOLO fatti veri da offers/products/testimonials)
- Elementi ricorrenti dei vincitori (metafore che funzionano, prove storiche, social proof specifico)
- Ancore tematiche (a cosa il copy deve sempre tornare)
- Livello di leggibilità (parole piccole: gratis, mio, voglio, paura, dolore — non parole da 50 euro)
- Errori da evitare — **ogni volta che l'AI sbaglia una cosa ricorrente, si aggiunge qui una regola**; regole di stile sempre presenti: em dash vietati, niente pattern-AI (vedi [scrittura.md](scrittura.md))

**Selezione dei riferimenti**: preferisci i vincitori del brand con risultati documentati. Se hai solo auto-monitoraggio, usa i candidati del bucket giusto selezionati per i segnali disponibili, dichiarando che la performance non è verificata (5–10 esempi per Starter, se presenti). Con meno esempi o senza dati, dichiara il limite e crea uno Starter provvisorio; non inventare casi vincenti.

## 2. Hook Prompt — `hook.md`

L'hook = le prime 10-20 parole (text ad) o i primi 5-10 secondi (video). È l'intero punto di decisione: se non guadagna il click, il resto dell'ad non esiste. Si genera SEMPRE prima del body.

```
Per questa idea, dammi 10 hook diversi. Saranno per [text ads long-form | video].

Ecco i miei hook vincenti come riferimento:
[HOOK ESTRATTI DALLE ADS MIGLIORI DEL BRAND — le prime 1-2 frasi di ciascun vincitore]

Ecco l'idea:
[IL BRIEF]

[CONTESTO AGGIUNTIVO: tono, angolo, elementi di prova desiderati, cosa deve
essere la paura/la promessa — è qui che si sterza l'AI, come negli esempi del
corso: "nessuno se ne frega che l'acqua sia elettricamente morta; gli interessa
che NUOCCIA. Fai quella la paura. Fai quello l'hook."]
```

Note di mestiere (dal corso): aperture ampie che non escludono nessuno ("La maggior parte delle persone non ha idea che…" include il lettore automaticamente); se gli output vanno nella direzione sbagliata, non accettare: dare contesto e sterzare.

## 3. Headline Prompt — `headline.md`

L'headline sta SOTTO l'immagine/video (non è la prima riga del copy): dichiarazione breve, call to action o proposta di valore.

```
Questo è il copy completato: [AD COMPLETA]

Ecco le mie headline che hanno performato: [HEADLINE PROVATE DEL BRAND]

Dammi 8 opzioni di headline: brevi, dichiarative, CTA o proposta di valore.
```

Regola di test: **2 headline per ad — una provata + una nuova**. La provata mantiene un riferimento già testato mentre si valuta una nuova proposta. Se non esistono headline provate del brand, proponine due nuove e dichiarale da testare. Le headline provate si accumulano in `headline.md` a ogni batch che performa.
