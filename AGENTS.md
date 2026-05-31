# Prosjektinstruksjoner

Dette prosjektet er en introduksjon til AI vibe coding for helt nye deltakere.

## Målgruppe

- Skriv for nybegynnere uten forkunnskaper om programmering.
- Forklar fagord første gang de brukes.
- Bruk norsk bokmål.
- Hold tonen trygg, praktisk og lite teknisk.

## Slides

- Hovedfilen for presentasjonen er `slides.md`.
- Bruk `presenterm`-kompatibel Markdown.
- Skill slides med `---`.
- Hold hver slide kort: én hovedidé, få punkter, store ord.
- Prioriter konkrete eksempler fremfor teori.
- Unngå engelske buzzord når et enkelt norsk ord fungerer.

## Tema

Presentasjonen skal lære deltakerne å bruke AI som en praktisk kodeassistent:

- beskrive ønsket resultat med vanlig språk
- teste små endringer
- lese og forstå forslag fra AI
- stoppe opp når noe virker feil
- jobbe iterativt: be, se, teste, justere

## Kjøring

Start utviklingsskallet og vis presentasjonen slik:

```sh
nix develop
presenterm slides.md
```
