# Creative Strategist · Certificlaude

Una skill per Claude Code che ti guida dalla lettura delle ads di un brand alla produzione di circa dieci nuovi annunci: **analisi, ideazione STORMING, preparazione dei prompt, scrittura**.

Puoi usarla in modalità **guidata**, prendendo le decisioni creative insieme a Claude, oppure **autonoma**, ricevendo un batch completo con le motivazioni delle scelte.

## Installa con una riga

Servono **Claude Code** già installato e **Git**. Non serve un account GitHub per scaricare un repository pubblico.

Incolla nel Terminale su macOS/Linux, oppure in **Git Bash su Windows**:

```bash
git clone https://github.com/copynerdai/creative-strategist.git ~/.claude/skills/creative-strategist
```

Poi apri una nuova sessione di Claude Code nella cartella del tuo progetto e scrivi:

```text
/creative-strategist
```

Puoi anche indicare subito il brand e la modalità:

```text
/creative-strategist IlMioBrand --auto
```

Se il comando di installazione segnala che la cartella esiste già, conserva la cartella esistente: potrebbe contenere una versione precedente o una tua skill. Se è già questa installazione, usa il comando di aggiornamento sotto.

La cartella `~/.claude/skills/` è la posizione delle skill personali di [Claude Code](https://code.claude.com/docs/en/skills#where-skills-live). Se usi `CLAUDE_CONFIG_DIR` per una configurazione personalizzata, sostituisci `~/.claude` con quella directory nel comando.

## Cosa preparare

- Nome del brand, prodotto, pubblico e offerta corrente.
- Ads e trascrizioni da analizzare, idealmente con dati che distinguano i vincitori.
- Prove reali utilizzabili: testimonianze, caratteristiche del prodotto, risultati documentati.

Se hai già **Copy Genius**, Claude può leggere le cartelle del tuo brand. Se non lo hai, ti aiuta a raccogliere il contesto essenziale.

**Brand Monitor / ad-scraping, organic-monitor e trascrizione locale sono integrazioni facoltative e separate.** La skill funziona anche con materiali che le fornisci direttamente; non include la raccolta automatica di ads, reel o commenti. Senza dati di performance, gli annunci osservati restano riferimenti creativi, non vincitori dimostrati.

## Cosa ricevi

Un archivio Markdown con note sui pattern, 20–40 semi di idee, circa dieci brief, i prompt del brand e le ads complete di **hook, body e headline**, più un report sulle fonti utilizzate. Puoi aprirlo anche con Obsidian.

L'archivio di lavoro viene tenuto nel tuo progetto, fuori dalla cartella installata. Il repository contiene soltanto istruzioni e prompt, così gli aggiornamenti restano separati dai tuoi dati. I materiali letti durante una sessione sono trattati secondo le impostazioni del tuo servizio Claude.

## Aggiorna

Per un'installazione proveniente da questo repository:

```bash
git -C ~/.claude/skills/creative-strategist pull --ff-only
```

Se hai modificato i file della skill e Git segnala un conflitto, conserva le modifiche e chiedi a Claude di aiutarti a integrarle.

## Dentro la skill

- [Processo e istruzioni](SKILL.md).
- [STORMING: le otto fonti di idee](prompt/storming.md).
- [Starter Prompt, Hook Prompt e Headline Prompt](prompt/asset-brand.md).
- [Sequenza di scrittura e revisione](prompt/scrittura.md).
