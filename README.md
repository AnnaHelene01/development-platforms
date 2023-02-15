# Development Platforms Course Assignment
## Anna Helene Sæthre
### 20.02.2023

# MySQL
### Introduksjon
MySQL er en åpen kildekode relasjonsdatabaseadministrasjonssystem (relational database management system) som blir brukt for webapplikasjoner, datavarehus og andre forretnings kritiske oppgaver.
Den ble utgitt i 1995 og har blitt en av de mest populære databasene i verden.

MySQL er kjent for sin skalerbarhet, pålitelighet og ytelse. Den håndterer store mengder data og er i stand til å støtte flere brukere og transaksjoner samtidig. MySQL støtter også ulike operativsystemer som Windows, Linux og Mac OS.

En av hovedfordelene med MySQL er dens brukervennlighet. Den har et enkelt og intuitivt grensesnitt, som gjør det lett for utviklere å lage og administrere databaser. I tillegg har MySQL et rikt sett funksjoner som gjør den egnet for et bredt spekter av bruksområder. 

En annen fordel med MySQL er sikkerhetsfunksjonene den har. Den har innebygd støtte for kryptering, sikre tilkoblinger og brukerautentisering som sikrer at data er trygg mot uautorisert tilgang. Den oppdateres jevnlig med sikkerhetsoppdateringer for å løse eventuelle sårbarheter som kan bli oppdaget. 


### Hoveddel
MySQL har et sterkt felleskap av utviklere og brukere som bidrar til utviklingen. Dette felleskapet har skapt et stort økosystem av plugins, verktøy og biblioteker som utvider funksjonaliteten og gjør MySQL enda kraftigere. 

Jeg satt opp min database med MySQL i PHPMyAdmin. For å gjøre dette logget jeg inn på PHPMyAdmin. Når du er logget inn for du en liste over eksisterende databaser til venstre på skjermen. For å lage en ny database klikker du på «New» knappen på toppen av skjermen.
I «create database/ny database» skjemaet som dukker opp, velger du navn til den nye databasen din og velger default karakter og sammenstilling. Du kan la det være på default med mindre du har spesifikke krav.
Klikk deretter på «create/opprett» knappen for å opprette den nye databasen din.
Når databasen er opprettet, kan du opprette tabeller og andre databaseobjekter ved å bruke knappen «create table/opprett tabell» eller ved å kjøre SQL queries i SQL tab/fanen. 
For å administrere innholdet i databasen din kan du bruke fanene «Insert/sett inn», «Delete/slett», «Update/oppdater» og «Select/velg» i PHPMyAdmin. 

I mitt tilfelle lagde jeg en handleliste, med skjema så jeg kunne legge til produkter etter behov.


Vi har også teknologien NoSQL som også mange velger å bruke. NoSQL refererer til en gruppe databaser som bruker en ikke-relasjonell datamodell. Her er noen fordeler og ulemper med begge:

Fordeler med MySQL:
- Gir en godt stukturert, pålitelig måte å lagre og administrere data på.
- Støtter komplekse spørsmål og relasjoner mellom dataene.
- Tilbyr utmerket datakonsistens og pålitelighet.
- Sterk transaksjonsstøtte, som gjør den ideell for økonomiske applikasjoner og andre saker det dataintegritet er kritisk.

Fordeler med NoSQL:
- Ideell for håndtering av ustrukturerte data.
- Tilbyr rask lese/skriveytelse.
- Skaleres horisontalt enkelt og effektivt.
- Tilbyr høy tilgjengelighet og feiltoleranse. 

Ulemper med MySQL:
- Ikke ideelt for ustrukturerte data.
- Kan være utfordrende å skalere horisontalt.
- Krever at et skjema defineres før data kan lagres.
- Muligens ikke det beste valget for programmer som krever høy skrivegjennomstrømning.

Ulemper med NoSQL:
- Begrenset støtte for komplekse spørsmål og dataforhold.
- Kan være mindre pålitelig enn tradisjonelle databaser.
- Tilbyr mindre datakonsistens, som er mindre ideell for transaksjonsapplikasjoner.
- Kan ha en brattere læringskurve, spesielt for utviklere som er vant til å jobbe med relasjonsdatabaser.

Valget mellom MySQL og NoSQL er mye avhengig av de spesifikke kravene til applikasjonen eller systemet som skal bygges. Begge har fordeler og ulemper, og utviklere må vurdere brukstilfeller, datamodeller og skalerbarhetskrav når de skal ta en beslutning på hvilken de skal bruke.


### Avslutning / konklusjon 
Avslutningsvis er MySQL en kraftig, brukervennlig og pålitelig database management system som blir mye brukt i denne bransjen. Funksjonene, skalerbarheten og sikkerheten gjør den til et ideelt valg for utviklere og bedrifter som ser etter en pålitelig databaseløsning.
Jeg syns det var ganske håndterlig og enkelt å lære. Veldig interessant og se hva som skjer før frontendern setter til verks, noe jeg også tror kan gjøre en frontender sterkere. 
