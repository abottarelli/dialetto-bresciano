# Dialetto bresciano · skill per AI

**Dialèt bresà** — una skill per insegnare alle intelligenze artificiali a scrivere, leggere e tradurre il dialetto bresciano.

*[English below](#english)*

---

## Cos'è

Gli assistenti AI conoscono bene l'italiano, ma sul bresciano sbagliano spesso: mescolano bergamasco e milanese, inventano parole, non distinguono i paesi. Questa skill è un insieme di istruzioni che l'AI legge prima di rispondere, con grafia, pronuncia, grammatica, lessico, detti, varianti locali e fonti.

Con la skill attiva l'AI può:

- **conversare** in bresciano, con o senza traduzione italiana;
- **tradurre** dall'italiano al bresciano e viceversa;
- **leggere** testi bresciani scritti in grafie diverse e spiegare come si pronunciano;
- **insegnare** la grammatica con esempi;
- usare le **varianti**: città e Bassa, Garda e Valtenesi, Val Trompia, Val Sabbia, Val Camonica, Franciacorta;
- indicare le **fonti** pubbliche per approfondire: vocabolari, Atlante Lessicale Bresciano, studi.

È una skill **solo testo**: non produce audio.

## Esempio

> **Tu:** Come si dice "domani vado a Brescia a comprare il pane"?
>
> **AI:** **Dumà nó a Brèsa a tö 'l pà.**
> *tö* = comprare/prendere; *nó* = vado. In Val Trompia: *Dumà nó a Brèha a tö 'l pà.*

## Come installarla

**Claude (app e sito claude.ai)**
Comprimi la cartella `skills/dialetto-bresciano` in un file .zip e caricalo dalle impostazioni delle skill di Claude. Poi basta scrivere in dialetto o chiedere "parliamo in bresciano".

**Claude Code**
In una sessione di Claude Code:

```
/plugin install dialetto-bresciano --marketplace abottarelli/dialetto-bresciano
```

**Altri strumenti compatibili con le Agent Skills**
Il file `SKILL.md` segue lo standard aperto [Agent Skills](https://agentskills.io). Con la CLI di skills.sh: `npx skills add abottarelli/dialetto-bresciano`. Oppure copia la cartella `skills/dialetto-bresciano` dove lo strumento si aspetta le skill.

**ChatGPT, Gemini e altre chat**
Copia il contenuto di `skills/dialetto-bresciano/SKILL.md` nelle istruzioni personalizzate, in un GPT personalizzato o in un Gem. Il risultato dipende anche da quanto quel modello conosce già il dialetto.

## Contribuire

Il bresciano cambia di paese in paese e nessuna fonte scritta lo copre tutto. Le correzioni di chi lo parla sono la parte più preziosa di questo progetto.

Se trovi un errore, una parola mancante o una forma diversa nel tuo paese, apri una **Issue** indicando:
- la forma giusta, scritta come la diresti;
- il **paese** dove si dice così;
- se possibile un esempio in una frase.

Vedi [CONTRIBUTING.md](CONTRIBUTING.md).

## Fonti

La skill si basa su fonti pubbliche, elencate nella sezione 10 del `SKILL.md`. Le principali: l'*Atlante Lessicale Bresciano* della Fondazione Civiltà Bresciana (G. Bonfadini), il *Vocabolario bresciano-italiano* del Melchiori (1817), il sito *Dialèt de Brèsa* di Marco Forzati, gli studi di Giovanni Bonfadini e le raccolte di detti di Pro Loco e associazioni locali.

I dizionari moderni protetti da diritto d'autore sono citati come riferimento ma **non** sono riprodotti nel progetto.

## Licenza

[CC BY-SA 4.0](LICENSE): puoi usarla, modificarla e ridistribuirla, anche per altri dialetti, citando l'autore e condividendo le modifiche con la stessa licenza.

Autore: Alberto, Bedizzole (BS).

---

## English

**An AI skill for the Brescian dialect** (*dialèt bresà*), the Eastern Lombard variety spoken in the province of Brescia, northern Italy (ISO 639-3: `lmo`).

AI assistants handle Italian well but struggle with Brescian: they mix it with Bergamasque or Milanese, invent words, and ignore local variation. This skill gives the model a compact reference it reads before answering: spelling, pronunciation, grammar, core vocabulary, proverbs, regional variants (city, Lowlands, Lake Garda, Valtenesi, Trompia, Sabbia and Camonica valleys, Franciacorta) and public sources.

With the skill active, the AI can converse in Brescian, translate Italian ↔ Brescian, read texts in different spelling systems and explain their pronunciation, teach grammar, and point to sources. Explanations are in Italian; text only, no audio.

**Install:** for Claude, zip the `skills/dialetto-bresciano` folder and upload it in Claude's skill settings; for Claude Code, run `/plugin install dialetto-bresciano --marketplace abottarelli/dialetto-bresciano`; with the skills.sh CLI, `npx skills add abottarelli/dialetto-bresciano`. The `SKILL.md` follows the open [Agent Skills](https://agentskills.io) standard, so it works in other compatible tools. For ChatGPT, Gemini and other chats, paste the `SKILL.md` content into custom instructions.

**Contributing:** native speakers' corrections are the most valuable part of this project. Open an Issue with the correct form, the town where it is used, and an example sentence.

**License:** [CC BY-SA 4.0](LICENSE). Feel free to fork it for other dialects and minority languages.

---

*Parole chiave / keywords: dialetto bresciano, dialèt bresà, Brescia, lingua lombarda, lombardo orientale, Garda, Valtenesi, Val Trompia, Val Sabbia, Val Camonica, Franciacorta, Bassa bresciana, Brescian dialect, Lombard language, Eastern Lombard, Italian dialects, minority languages, AI skill, Claude skill, Agent Skills.*
