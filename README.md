# Teknisk dokumentation for Tema 8 gruppeprojekt - gruppe 1

Når man er flere der bidrager til en kodebase, lærer man hurtigt, at ens sædvanlige måder at gøre tingene på ikke nødvendigvis er logisk for alle.

Skriv derfor jeres fælles retningslinjer for punkterne herunder(tilføj gerne flere selv), sådan som det giver bedst mening for jer som gruppe. Dokumentationen sikre, at jeres fælles kodebase forbliver overskuelig, er let at arbejde med og til at forstå for alle, og at I undgå konflikter, og har nemmere ved at hjælpe hinanden undervejs.

## Projektstruktur:

Beslut, hvordan I vil organisere jeres projekt – struktur for mapper og filer.

- Vi ville gerne have en simpel mappe- og filstruktur, så alle i gruppen nemt kunne have overblik over projektet.

- Vi oprettede vores projekt via astro, og derfra prøvede vi at få struktur i de mapper, der blev oprettet af denne vej.

## Navngivning:

Hvordan navngiver I filnavne? (fx små bogstaver, ingen mellemrum, brug af - eller \_)

- Vi har gennemgående navngivet vores filer med små bogstaver, uden mellemrum og brug af underscore. På den måde har vi kunnet sikre konsistens i strukturen. Desuden er det vigtigt med denne kontinuitet for, at der ikke ville opstå problemer i URL’en på sitet og at siderne ikke kan findes korrekt, når man søger på dem. Dog har vi navngivet vores astro-filer med stort startbogstav for at sikre konsistens.

## Git branches:

Hvordan navngiver I branches, så alle kan forstår hvem der arbejder i branchen og på hvad?(fx feature-lotte-formular)

- Som udgangspunkt forsøgte vi at navngive vores branches ud fra, hvad for noget indhold der var i gang med at blive arbejdet på deri. Fx. index laves, kontaktformular oprettes etc. Det gjorde vi for at holde det simpelt og nemt at forstå, hvad der blev lavet hvor. Virkeligheden var dog, at vi oplevede nogle problemer med vores git og branches, så der kom flere branches med afarter af det samme navn og også nogle med navnet test for at få det hele til at fungere. Dog havde vi på forhånd aftalt mundtligt, hvem der arbejdede på hvad, og derfor vidste vi godt, hvilke branches der hørte til hvem.

## Arbejdsflow:

Hvordan fordeler I arbejdet, så I undgår at flere arbejder i de samme filer samtidigt?

- Vi sørgede for at lave en mundtlig aftale, som vi gennemgik hver dag, hvor vi fandt ud af, hvem der lavede hvilke komponenter. Så satte vi vores komponenter ind på vores sider, når vi sad samlet netop for at undgå, at vi arbejdede i de samme filer samtidigt.

Hvordan sikrer I, at commit-beskeder er beskrivende?

- Vi har forsøgt at lave korte og præcise beskrivelser, så de er lette at forstå for alle, hvori vi beskriver, hvad der er blevet lavet, hvor og/eller på hvilken side.

Hvordan kommunikerer I om ændringer i main branchen når feature merges?

- Vi har været gode til at huske hinanden på at pull i main for at hente nyeste ændringer, inden man selv foretager sig noget. Derudover har vi generelt prøvet at huske hinanden på de forskellige trin, der er med alt fra at lave en ny branch, stage ændringer, commit, pull, push og merge, ligesom vi har siddet meget sammen, hvorfor det har været nemt at snakke højt om det.

## Kode:

- Vi har oprettet vores forskellige komponenter fra vores Figma-prototype i VS Code. Vi har lavet en footer, header, knapper, eventcards, filterkategori, filter på tid, hero-sections, tidsplan og en Instagram-scrollbar. Vi har lavet dem i hver deres astro-fil, hvori vi har lavet strukturen for dem og designet dem individuelt.

Derefter har vi indsat vores komponenter på henholdsvis vores forside og vores programside. Det smarte med komponenterne er, at man kan sætte dem ind med forholdsvis lidt tekst på de sider, hvor de skal være og så imporere siderne i toppen af sitet fx således: "import Instascroll from "../components/Instascroll.astro";"

# Funktionalitet

Dette afsnit skal forklare hvad I konkret har arbejdet med for at udvikle websitet. Tænk over hvilke interaktioner brugeren kan foretage på sitet? Eller hvordan websitet håndterer og præsenterer data?

Brug korte beskrivelser

Filtrering af produkter:

- Vi har indsat en mulighed for filtrering på vores programside. Her kan man vælge at filtrere på kategorier eller på tid. Lige nu er den ikke funktionel, men man kan fornemme, hvad idéen er. Til videre udvikling kan man gøre den dynamisk, så man kan krydse kategorierne af og faktisk få filtreret sin side.

Knap til at switche mellem dansk og engelsk:

- Vi har i vores menu indsat en knap, hvor det skal være muligt at skifte mellem dansk og engelsk. Det kan man endnu ikke gøre på vores kodede site, men det virker i prototypen. Tanken er, at man på den måde kan inddrage internationale gæster endnu mere.

Scroll-menu af Instagram-posts:

- På vores forside har vi indsat en en scroll-menu med forskellige Instagram-posts. På den måde kan man se, hvad der bliver delt fra Helsingør Kulturnat. Dette er på baggrund af et ønske fra målgruppen.
