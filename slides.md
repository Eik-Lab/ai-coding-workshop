---
title: AI vibe coding
sub_title: Fra null til helt med AI-koding
author: Eik Lab
theme:
  override:
    intro_slide:
      title:
        font_size: 4
---

# Agenda

1. Hva er AI vibe coding?
2. Oppsett: opencode + VS Code-utvidelsen
3. Styre AI-en: AGENTS.md, skills og plan-modus

<!-- end_slide -->

# Hva er AI vibe coding?

## Vibe coding, kort fortalt

- Du **beskriver** hva du vil ha — med vanlig språk.
- En **AI-assistent** foreslår koden.
- Du **leser, tester og justerer** sammen med den.

Du trenger ikke kunne skrive koden selv for å komme i gang.

<!-- end_slide -->

# Arbeidsflyten

1. **Be** — fortell hva du vil ha. Gjerne kom med referanse caser.  
  - e.g link til en nettside som inspirerer
2. **Se** — les forslaget AI-en gir.
3. **Test** — kjør koden og sjekk om det virker.(Hint: Du kan be AI-en gjøre dette for deg!)
4. **Juster** — be om en liten endring, og gjenta.

Små steg slår store sprang.

<!-- end_slide -->

# Hva det _ikke_ er

- Ikke magi — AI-en kan ta feil.
- Ikke en erstatning for å tenke selv.
  - Don't drunk drive!
- Ikke "ferdig" før du har testet det.

> Stopp opp når noe virker rart. Spør heller én gang for mye.

<!-- end_slide -->

<!-- jump_to_middle -->
<!-- alignment: center -->
<!-- font_size: 6 -->

**Oppsett**

<!-- font_size: 2 -->

opencode + VS Code

<!-- end_slide -->


# Hva er opencode?

- En **AI-kodeassistent** du snakker med i terminalen eller editoren.
- Åpen kildekode — gratis å bruke.
- Fungerer rett i prosjektmappen din.

Nettside: `opencode.ai`
<!-- end_slide -->

# Steg 1: Installer opencode

I terminalen:

```bash
curl -fsSL https://opencode.ai/install | bash
```

Eller med Homebrew (Mac):

```bash
brew install anomalyco/tap/opencode
```

<!-- end_slide -->

# Steg 2: VS Code-utvidelsen

1. Åpne VS Code.
2. Åpne terminalen inne i VS Code.
3. Skriv `opencode` og trykk enter.

Utvidelsen installeres automatisk første gang.

<!-- end_slide -->

# Steg 3: Logg på en modell

I denne presentasjonen bruker vi de gratis modellene til opencode. 

I opencode:

```text
/connect
```

Følg lenken, logg inn, lim inn API-nøkkelen.

Da er du klar til å prøve.

---

# Første prøve

Be om noe lite og konkret:

```text
Lag en HTML-side som sier "Hei verden" med en blå knapp.
```

Les forslaget. Kjør det. Be om én endring av gangen.

<!-- end_slide -->

<!-- jump_to_middle -->
<!-- alignment: center -->
<!-- font_size: 6 -->

**Styre AI-en**

<!-- font_size: 2 -->

AGENTS.md, skills og plan-modus

<!-- end_slide -->

# Hvorfor styre den?

- AI-en gjetter ut fra det den ser.
- Mer **kontekst** og tydeligere **regler** gir bedre svar.
- Du slipper å forklare det samme om og om igjen.

> Sett rammene én gang — høst gevinsten hver gang.

<!-- end_slide -->

# AGENTS.md — prosjektregler

En fil i prosjektmappen som forteller AI-en:

- Hva prosjektet handler om.
- Hvilket språk og hvilken tone.
- Hva den skal og ikke skal gjøre.

AI-en leser den automatisk hver gang.

<!-- end_slide -->

# Skills — gjenbrukbare oppskrifter

En **skill** er en ferdig "fremgangsmåte" du gir AI-en.

- Eksempler: "skriv commit-melding", "lag presentasjon", "kjør tester".
- AI-en henter den frem når oppgaven passer.
- Du bygger opp et bibliotek over tid.

<!-- end_slide -->

# Plan-modus — se planen først

Før AI-en endrer kode, kan du be om en **plan**.

1. Trykk `Tab` i opencode for å bytte til plan-modus.
2. Beskriv hva du vil ha.
3. Les planen, juster, og godkjenn.
4. Trykk `Tab` igjen for å bygge.

Færre overraskelser, mindre opprydning.

<!-- end_slide -->

<!-- jump_to_middle -->
<!-- alignment: center -->
<!-- font_size: 7 -->

**La oss prøve!**
