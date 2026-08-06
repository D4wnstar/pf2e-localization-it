# Pathfinder 2e Italian Localization

> (Italian version below)

This package provides partial Italian localization data for the FoundryVTT [Pathfinder 2e system](https://github.com/foundryvtt/pf2e). The localization was, where possible, ported from official book localizations, the public OGL parts of which are uploaded by the Italian Pathfinder community on the [Golarion Insider wiki](https://pf2.altervista.org/wiki/Pagina_principale). Remaining content that has either not been added to Golarion Insider or has yet to receive an Italian localization at the time of writing has either been hand-translated or not translated at all.

The text was ported as identically to the source as possible, with typo fixes and casing changes being the only common adjustments. However, as all currently-released Italian localizations are from before the PF2e Remaster project, but the PF2e Foundry system is up-to-date with the Remaster, many localization strings were updated by hand to make them match the remastered version if there were any discrepancies.

"Content" here means "the localization strings of the `foundryvtt/pf2e` system", generally used with the `_loc` function.

Localizing Starfinder 2e content is not a goal of this package as there is no official Italian localization yet. However, since SF2e uses the same Foundry system as PF2e, much of Pathfinder's translation should be automatically applied to Starfinder. Further, a small part of Starfinder's unique content was translated on a best-effort basis. Note that none of these were tested in practice.

Some wording changes have been applied to the official translation for a variety of reasons, mostly clarity, consistency and/or correctness. The full list is at the bottom of this page.

## Contents

This localization is very much incomplete. Right now, it only includes localization of these language files:
- `en.json` (general content).
- `action-en.json` (basic and skill actions).
- `kingmaker-en.json` (Kingmaker content).

These files are used for system data, such as displaying all sheets like PC, NPC and item sheets, as well as for generating chat messages. The localization does not include:
- `re-en.json` (rules element text).
- `sf2e-overrides-en.json` (SF2e specifics).
- Any content in compendia, like spells, feats, etc.

The lack of compendium content (Foundry items and journals) is why you will notice some bizarre inconsistencies, such as the page for the Shove action (a Foundry item) being in English, but the chat message of the Shove action macro (a generated chat message) being in Italian, despite in theory being the same text.

## Legal

Italian localization that is ported as-is is licensed under the OGL v1.0a. Italian localization that has been updated to match remaster terminology is dual-licensed under both the OGL v1.0a and the ORC License, as it is Derived Content under both.

## Versioning

This package's major and minor version represent the major and minor versions of the `foundryvtt/pf2e` lang files this package is (mostly) up to date with. Patches are for updates specific to this package, like fixing typos, terminology updates, adding translations for missing content of older versions and so on.

---

# Localizzazione Italiana per Pathfinder 2e

Questo pacchetto contiene dati per una localizzazione parziale del [sistema Pathfinder 2e](https://github.com/foundryvtt/pf2e) per FoundryVTT. La localizzazione è stata, ove possibile, derivata da localizzazioni ufficiali di libri, le cui parti OGL pubbliche sono pubblicate dalla community italiana di Pathfinder sulla [wiki Golarion Insider](https://pf2.altervista.org/wiki/Pagina_principale). I contenuti rimanenti che non sono stati aggiunti su Golarion Insider o che non hanno ancora ricevuto una localizzazione al momento di scrittura di questo README o sono stati tradotti a mano o non sono proprio stati tradotti.

Il testo è stato adattato quanto più identicamente possibile alla fonte, con al più correzioni di errori di battitura e maiuscole/minuscole nella maggior parte dei casi. Tuttavia, dato che tutte le localizzazioni finora pubblicate sono antecendenti al progetto Remaster di PF2e, ma il sistema Foundry è aggiornato al Remaster, molte stringhe di localizzazione sono state aggiornate a mano per farle combaciare con le nuove versioni remaster in caso di discrepanze.

Per "contenuti" qui s'intende "le stringhe di localizzazione del sistema `foundryvtt/pf2e`", quelle in genere usate con la funzione `_loc`.

Localizzare Starfinder 2e è fuori ambito per questo pacchetto, dato che non c'è ancora una localizzazione ufficiale. Tuttavia, dato che SF2e usa lo stesso sistema Foundry di PF2e, molte delle traduzioni di Pathfinder dovrebbero essere applicate in automaticato anche a Starfinder. In più, una piccola parte di contenuti specifici a Starfinder è stata tradotta laddove la traduzione fosse piuttosto ovvia. Nessuna di queste traduzioni è però stata testa in pratica.

Alcuni cambiamenti ai termini rispetto alla traduzione ufficiale sono stati compiuti per un misto di ragioni, perlopiù chiarezza, coerenza e/o correttezza. La lista intera è in calce alla pagina.

## Contenuti

Questa localizzazione è molto incompleta. Per ora, include solo la localizzazione di questi file di lingua:
- `en.json` (contenuti generali).
- `action-en.json` (azioni base e di abilità).
- `kingmaker-en.json` (contenuti di Kingmaker).

Questi file sono usati per dati di sistema, quali il testo delle schede dei PG, PNG and oggetti, così come la generazione di messaggi in chat. La localizzazione non include:
- `re-en.json` (testo degli elementi di regole).
- `sf2e-overrides-en.json` (stringhe specifiche a SF2e).
- Qualunque contenuto in compendi, come incantesimi, talenti, ecc.

La mancanza di contenuto dei compendi (*items* e *journals* di Foundry) è la ragione per cui noterai alcune bizzarre incongruenze quali ad esempio la pagina per l'azione Spingere (un *item* di Foundry) in inglese, ma il messaggio in chat della macro per Spingere (un messaggio generato) in italiano, nonostante in teoria siano lo stesso testo.

## Legale

La localizzazione italiana copiata così com'è è autorizzata sotto la OGL v1.0a. La localizzazione italiana adattata alla terminologia remaster è autorizzata simultaneamente sotto la OGL v1.0a e la Licenza ORC, poiché è Derived Content secondo entrambe.

## Versionamento

La versione maggiore e minore di questo pacchetto rappresentano la versione maggiore minore dei lang files di `foundryvtt/pf2e` alla quale questo pacchetto è (perlopiù) aggiornato. Le patch indicano cambiamenti specifici a questo pacchetto, tipo correzioni di errori di battitura, cambiamenti di terminologia, aggiunta di nuove traduzioni mancanti da versioni più vecchie e via avanti.

# Variazioni alla traduzione ufficiale

## Meccaniche generali

| Originale | Ufficiale | Variazione | Ragione                                                                                          |
| --------- | --------- | ---------- | ------------------------------------------------------------------------------------------------ |
| Bulk      | Volume    | *Ingombro* | L'intero scopo della meccanica è combinare e astrarre volume e peso, non ha senso chiamarla Volume |

## Condizioni

| Originale   | Ufficiale       | Variazione    | Ragione                                                                                                          |
| ----------- | --------------- | ------------- | ---------------------------------------------------------------------------------------------------------------- |
| Drained     | Risucchiato     | *Prosciugato* | Più naturale                                                                                                       |
| Unconscious | Privo di Sensi  | *Svenuto*     | Più conciso e funge anche da verbo ("A 0 PF, svieni")                                                            |
| Undetected  | Non Individuato | *Inosservato* | Questi termini sono molto confusi anche in inglese, questo è un tentativo a renderli leggermente meno spiacevoli |
| Unnoticed   | Inosservato     | *Inavvertito* | Come sopra                                                                                                       |

## Abilità e azioni

| Originale        | Ufficiale                | Variazione               | Ragione                                                                                                                                                                 |
| ---------------- | ------------------------ | ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Grapple          | Lottare                  | *Afferrare*              | In 2e, Grapple non è lottare avvinghiato, è solo afferrare qualcuno con una mano libera. L'ufficiale è un vestigio di 1e. Le lotte sono proprie dell'archetipo Wrestler |
| Avoid Notice     | Evitare l'Individuazione | *Passare Inosservato*    | Più naturale                                                                                                                                                            |
| Detect Magic     | Individuare il Magico    | *Individuare Magia*      | Più naturale                                                                                                                                                            |
| Seek             | Individuare              | *Cercare*                | Più naturale e rispecchia meglio l'uso                                                                                                                                  |
| Decipher Writing | Decifrare Scritti        | *Decifrare Testi*        | Più naturale                                                                                                                                                            |
| Subsist          | Sopravvivere             | *Sostentarsi*            | Più corretto, nonché privo della collisione con l'abilità Sopravvivenza                                                                                                 |
| Sneak            | Muoversi Furtivamente    | *Sgattaiolare*           | Più naturale                                                                                                                                                            |
| Palm an Object   | Nascondere nella Mano    | *Agguantare un Oggetto*  | Più corretto e rispecchia meglio l'uso                                                                                                                                  |

## Classi e privilegi di classe

| Originale       | Ufficiale                | Variazione              | Ragione                                |
| --------------- | ------------------------ | ----------------------- | -------------------------------------- |
| Overflow        | Esubero                  | *Sovraccarico*          | Più chiaro                             |
| Power Suit      | Armatura del Potere      | *Armatura Motorizzata*  | Davvero? Armatura del Potere?          |


## Armi

| Originale     | Ufficiale                               | Variazione              | Ragione                                                                        |
| ------------- | --------------------------------------- | ----------------------- | ------------------------------------------------------------------------------ |
| Air Repeater  | Pistola a Ripetizione ad Aria Compressa | *Ripetitore Pneumatico* | Ufficiale estremamente verboso                                                 |
| Bo Staff      | Bastone Bō                              | *Bastone Bo*            | Ragioni tecniche per evitare caratteri speciali                                |
| Greataxe      | Grande Ascia                            | *Ascia Pesante*         | Più in linea con termini standard del genere                                   |
| Longsword     | Spada d'Arme                            | *Spada Lunga*           | Come sopra, nonché errato: le spade d'arme erano spade corte di 60-70 cm       |
| Rapier        | Spada da Lato                           | *Stocco*                | Come sopra, e spada da lato è un po' generico, stocco o striscia è più preciso |
| Monkey's Fist | Pugno di Scimmia                        | *Pugno della Scimmia*   | Ufficiale manca del possessivo                                                 |

## Materiali

| Originale | Ufficiale | Variazione | Ragione                                         |
| --------- | --------- | ---------- | ----------------------------------------------- |
| Abysium   | Abysium   | *Abissio*  | Non capisco perché l'ufficiale non sia tradotto |

## Creature

| Originale   | Ufficiale     | Variazione      | Ragione                                                                                                                               |
| ----------- | ------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Phantom     | Apparizione   | *Anima Errante* | Termine purtroppo molto affollato: Fantasma e Spettro sono già usati altrove, mentre Apparizione adesso è preso dalla classe animista |
| Serpentfolk | Uomo Serpente | *Serpentide*    | Mette in linea con altre stirpi "-folk" tradotte come "-ide"                                                                          |

## Tratti

| Originale | Ufficiale        | Variazione      | Ragione                                                                                                                              |
| --------- | ---------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Backswing | Recupero         | *Slancio*       | Più chiaro, permette variazione sotto                                                                                                |
| Recovery  | Richiamabile     | *Recupero*      | Ufficiale collide con la runa di proprietà Richiamabile                                                                              |
| Sweep     | Spazzare         | *Spazzata*      | Tipicamente i tratti sono sostantivi, non verbi                                                                                      |
| Halcyon   | Halcyon          | *Alcionio*      | Alcionio è anche una parola italiana! Arcaica e proveniente dal greco antico, con lo stesso significato inglese di "placido, sereno" |
