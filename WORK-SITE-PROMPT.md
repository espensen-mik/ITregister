# Prompt til ChatGPT Work / Sites

Jeg vil have publiceret denne webapp som et ChatGPT Site.

## Formål
Appen er LykkeLigas interne IT-register og skal fungere som et lille kontrolcenter over vores IT-systemer, software, licenser og egne digitale løsninger.

## Krav
- Bevar det eksisterende mørke “Warroom / Control Center”-design.
- Bevar alle eksisterende systemer, priser, noter, kategorier og statusser.
- Bevar funktionerne til:
  - at tilføje nye systemer
  - at redigere alle oplysninger i modal
  - pris pr. måned
  - automatisk beregning af pris pr. år
  - status: Aktiv / Undersøg / Opsig
  - søgning og filtrering
  - samlet årlig softwareudgift
  - hurtig beregning, hvor man kan vælge flere licenser og se deres samlede årspris
  - sletning af systemer
- Google Workspace skal være én samlet post; Gmail, Drive, Docs, Sheets og Chat skal ikke være separate poster.
- Appen skal have enkel adgangsbeskyttelse med kodeordet: Mikaelersej
- Data skal være fælles/persistente, så mine kolleger ser de samme ændringer – ikke kun browserens localStorage.
- Migrér de medfølgende registerdata til den persistente lagring ved første publicering.
- Publicér som et ChatGPT Site og giv mig den færdige URL.

## Vigtigt om data
Hvis der ligger en fil med navnet `lykkeliga-it-register-backup.json` i uploaden, er den den autoritative seneste version af registerdataene og skal bruges som seed/import ved publicering.
Hvis den ikke findes, skal data fra den medfølgende app bruges som udgangspunkt.


## Autoritativt registerdata
Filen `lykkeliga-it-register-backup.json` i denne ZIP er den aktuelle version af brugerens register og skal importeres 1:1 som startdata. Bevar alle priser, noter, statusser, kategorier, månedspriser og systemnavne.
