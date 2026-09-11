# STORMING — le 8 fonti di ideazione

> Usato dall'orchestratore nella Fase 2. Obiettivo: **20-40 semi grezzi**, senza filtrare, in `semi-<anno>.md`. Ogni seme: 1-3 righe + bucket (`U/P` o `S/P`) + fonte (S/T/O/R/M/I/N/G). Il corso lo chiama "overkill deliberato": non serve far girare tutte le fonti ogni volta, ma la sessione completa produce idee per un mese.
> Regola trasversale: durante lo Storming NON si giudica e NON si scrive copy. Si raccoglie.

---

## S — Swipe (ads di ALTRI brand)

Non per copiare: per trovare energia, struttura o angolo di un'idea e adattarla. Tre categorie di brand, tutte e tre da passare:
1. **Concorrenti diretti** · 2. **"Cugini"** (problemi adiacenti, stesso pubblico) · 3. **Non correlati** (le idee più fresche: un hook che funziona altrove, adattato qui, è il più inaspettato).

**Fonte dati**: ads e analisi di altri brand fornite dall'utente, oppure archivio di brand-monitor quando disponibile (`monitoraggio/<osservato>/creativita-<anno>.md` e `analisi-<anno>.md`). Se mancano cugini o non-correlati, segnalalo nel report; aggiorna la raccolta via `/ad-scraping` solo se la skill è disponibile, altrimenti chiedi materiali all'utente.

**Prompt**: «Leggi queste analisi di ads di altri brand [incolla le sezioni angolo/hook]. Per ciascuna che ha energia trasferibile: estrai il MECCANISMO dell'hook (non le frasi) e proponi 1 adattamento al [prodotto], nel suo mercato. Formato: seme di 1-3 righe.»
👤 In guidata l'utente scorre le analisi e dice quali lo accendono; in autonoma sceglie la skill.

## T — Template (stampi provati)

Fonte: swipe library e strutture del progetto, se disponibili, oppure template forniti dall’utente o estratti dagli annunci analizzati. Distingui gli stampi di riferimento dai template con risultati verificati.

**Prompt**: «Queste sono le ads vincenti del brand [corpus per bucket]. Questi sono template/swipe provati [incolla]. Scegli i 10-12 template più adatti al [prodotto] e per ciascuno scrivi il CONCETTO di ad (non il copy): un seme di 1-3 righe.» Selezionare poi solo le 1-2 idee che danno convinzione.

## O — Organico (reel IG/TikTok) — una delle più potenti

Logica: i reel virali hanno GIÀ vinto l'asta dell'attenzione. Il segnale non è "video bello": è l'**outlier** — un creator che fa 2.000 view di media e ha un video da 500.000. Quell'idea specifica ha risuonato. Commenti alti = segnale aggiuntivo.

**Principio del collegamento forzato**: qualsiasi idea può essere collegata a qualsiasi prodotto. Più il reel sembra scollegato, più l'hook risulterà fresco: si riprende il meccanismo e l'energia dell'hook, scrivendo frasi proprie e si costruisce il ponte logico verso il prodotto. È anche l'antidoto alla stagnazione creativa dell'AI (che ricicla le stesse idee: l'organico inietta sangue nuovo).

**Accesso ai materiali**: segui le integrazioni descritte in `SKILL.md`. Usa un repertorio organic-monitor già disponibile oppure i materiali forniti dall'utente. Per un link, leggi solo ciò che gli strumenti disponibili consentono davvero; per audio e video usa una trascrizione locale disponibile o chiedi il testo.
- Guidata: l'utente seleziona i materiali; la skill analizza hook, struttura e commenti disponibili.
- Autonoma: la skill seleziona dal corpus accessibile; se manca, dichiara la fonte non utilizzata.
- Verifica l'outlier solo quando conosci le view del video e una base di confronto del creator. Senza questi dati chiamalo riferimento, non outlier verificato. Registra creator e provenienza in `creators.md`.

## R — Ricerca & Commenti (il pubblico che parla tra sé)

Si cerca: **linguaggio esatto, storie personali, paure, credenze, obiezioni** — le parole a cui il pubblico ricorre spontaneamente. Un commento può diventare direttamente un concetto di ad (nel corso: il commento dell'ustione → l'ad "Unità Ustionati").

**Fonti**: `storie-linguaggio-cliente.md` (aggiunte progressive con provenienza), testimonianze e ricerca del brand, commenti ed esportazioni forniti dall'utente. Recensioni, forum e commenti pubblici si usano solo quando realmente accessibili attraverso gli strumenti disponibili. Distingui citazioni verbatim, parafrasi e ipotesi.

**Prompt**: «Leggi questi materiali verbatim del pubblico [incolla]. Estrai: 1) vocabolario emotivo ricorrente (parole esatte), 2) storie personali che possono diventare hook, 3) obiezioni ricorrenti, 4) angoli inaspettati. Per ognuno un seme.»

## M — Matrice (combinazioni)

Si usa DOPO le altre fonti: combina meccanicamente ciò che è emerso per generare accostamenti inaspettati.

**Prompt**: «Ecco i semi raccolti finora [incolla]. Costruisci una matrice: righe = angoli/meccanismi emersi, colonne = formati e leve emotive dei vincitori. Proponi 5-8 combinazioni NON ovvie (incroci mai tentati nell'account). Un seme ciascuna.»

## I — Vettori interni (LA FONTE PIÙ IMPORTANTE — due passaggi)

Pattern dei propri vincitori + osservazioni umane → idee radicate in ciò che è già provato. **Il secondo passaggio è dove avviene la magia.**

**Passaggio 1 (in parallelo):**
- AI: «Processa tutte queste ads vincenti [corpus del bucket]. Presta attenzione ai pattern specifici per cui funzionano, cogli i pattern profondi, e dammi nuove idee basate su quei pattern.»
- 👤 Nel frattempo l'umano rilegge i vincitori e prende appunti SUOI (temi, toni, prove, hook ricorrenti): l'umano vede pattern che l'AI non vede, e viceversa.

**Passaggio 2 (la fusione):**
- «Ecco le mie osservazioni: [narrazione — pattern notati, storie clienti, obiezioni sentite ogni giorno, cosa dicono i clienti che spendono di più…]. Combina questo contesto con la tua analisi e rigenera le idee.»
- In autonoma, le "osservazioni" si costruiscono da: Note pattern di `vincitori.md` + conoscenza brand (avatars, research, testimonials) + storie-linguaggio-cliente. Dichiarare che sono ricostruite, non narrate.

Qui l'imprenditore è imbattibile: il contesto che solo lui ha ("il problema vero non è X, è che si sentono Y e non vogliono ammetterlo") produce idee che nessun esterno raggiunge. In guidata, questo è IL momento di narrare.

## N — Nuovi stili (il formato È l'hook)

Formati visivi/strutturali emergenti visti nell'organico (claymation, prodotti parlanti, narrazione in prima persona di un ingrediente…): se uno sta prendendo trazione e si può eseguire, si scrive un'ad progettata apposta per quel formato. Freschi e precoci: si lancia prima che saturi. Stato: deriva dalla fonte O (stesso fallback).

## G — Gambetti (cervello a strumenti spenti)

Ultima fonte, DOPO tutte le altre: il cervello è innescato dai pattern assorbiti. 2-5 idee libere, senza AI, senza template, senza swipe — non devono essere le migliori, tengono affilato il pensiero.
- Guidata: 👤 l'utente, 10 minuti, la skill sta zitta e poi trascrive.
- Autonoma: la skill fa brainstorm usando SOLO la conoscenza del prodotto/pubblico/cultura (niente corpus, niente semi già raccolti sul tavolo).

---

## Chiusura dello Storming

1. Tutti i semi in `semi-<anno>.md`, marcati con bucket + fonte, SENZA filtrare (il master doc è un asset che cresce: i semi non usati restano nel vivaio).
2. 👤 Selezione: ~10 semi → brief in `brief/<data>-batch.md`. Un brief = poche frasi col nucleo e la spinta principale, come spiegheresti il concetto a un copywriter junior (voice-to-text benvenuto). Hook incluso solo se c'è già. MAI troppe informazioni.
3. Rispetta le proporzioni dei bucket: ~60-70% U/P, ~30-40% S/P.
