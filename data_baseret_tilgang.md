Den data baserede løsning/process tilgang

# Hvordan det burde være (funktionerne)

## Forretningsudvikler/digitaliseringskonsulent

- Kontakt og overblik over forretningens behov
- Indsamler viden fra fronten om hvor der er friktion i processer
- Beskriver processer
- Grundlæggende forståelse af teknologiske muligheder
- Inspirere forretningen til at tænke nyt
- Skitsere projektideer og afklarer med Data scientist, IT-arkitek og
  fremlægger for chefer 

## Chefer

- Træffer oplyste strategiske beslutninger om retning og ressource allokering
- Efterspørger inputs til afklaring af tekniske spørgsmål og tester dig
  sammenhæng/årsagsforståelse ved eksperterne

## Data Inginiører/Data Engineer

- udvikler/opsætter integrationer fra "fag"-systemer til databaser (ekstrehere
  data)
- vurdere relevant metadata
- Beriger data med metadata
- Ændre evt dataformat, frekvens eller lignende til et (mere) standardligseret
  format

## IT-arkitekt

- Har overblik over hele forretningen (inkl. udviklingsafdelingens) IT
  tekniske infrastruktur.
- Sikre at Data ingeniørerne, DevOps, MLOps, Data Scientist, udviklere har
  platformene til at arbejde og at der er velbeskreve tekniske processer for
  arbejdet.
- Besvare chefens spørgsmål indenfor sit område og giver anbefalinger

## Entreprise-arkitekt

- Har overblik over hele forretningens processer og job-funktioner
- Sikre at organisationen har muligheden for at løse de strategiske mål som
  chefen beslutter
- Besvare chefens spørgsmål indenfor sit område og giver anbefalinger, der sikre
  at organisationen kan løfte udviklingsopgaverne

## DevOps

- Sikre at IT-systemerne kører, monitorerer og opdatere

## MLOps/ML Engineer

- Sikre at statiske modeller der bruges i data baserede løsninger/processer
  kører
- overvåger at data grundlaget ikke ændre sig så meget at det data man byggede
  modellen på ikke længere er repræsentativt
  - gentræner i så fald modellen
- (For ML engineer) træner modellen i første omgang

## Data Scientist

- Undersøger hvilken data der er nødvendig for at løse et givet problem.
  Eksplorativt dataanalyse
- Fastlægger kriterier for (i hvilket omfang) en model/løsning løser den
  tekniske opgave: Evaluerer
- Undersøger hvordan der bør/kan trækkes data ud af observationer (ofte kan
  observationer være andet data eks. et fritekst felt, man vil vide om det er
  positivt stemt eller et billede hvor man vil vide om der er en bil til stede)
  eller rydde op i data: Data wrangling/cleaning
- Udvælger statiske model arkitekturer (sandsynligheder for regn) eller
  definere bare triggers (luk vinduer når trykket falder med x pascal)
- Indsamler data - evt. sammen med data engineer
- (Evt ML Engineer) Træner model
- (Evt ML Engineer) Sikre at modellen spiller ind i den tekniske løsning sammen
  med backend-udvikleren

## Projektledere

- Balancerer de andres opgaver, så der er mindst mulig friktion/venten på at
  andre bliver klar
- Sørger for at opgaver er beskrevet klart nok til at dem der skal løse dem
  forstår hvad de skal gøre

## Frontend udviklere / UI

- Laver brugergrænsefladen der gør løsningen brugbar for brugerne

## Backend udviklere

- Udvikler løsningen

## UX'ere 

- Designer hvordan løsningen kommer til at indgå i brugernes arbejde


# Hvordan det er i virkeligheden

NB: man ansætter ikke funktioner, men ansætter mennesker og i praksis 
kan de altid dække flere funktioner

Så en given person vil ofte dække flere funktioner, men det afhænger så også af
personen hvilke funktioner vedkommende har kompetancerne til at varetage.


## NB: VI skal bare have mere data!!!
Nej!

__Alle__ observationer kan omsættes til data, men data fylder. 
Data er kun relevant når det kan skabe værdi (værdi kan også være i form af
dokumentation, så handler det bare ikke om at løse/understøtte umiddelbare
problemer/usecases). Data-"rejsen" starter derfor med en use-case, der kan laves
observationer omkring. Observationerne kan omsættes til data, der kan
_understøtte_ en løsning af et problem eller en forbedret process.

Hvis man begrænser sig til at kigge på hvilke problemer man kan løse med data
man allerede har, så begrænser man sig selv meget kraftigt i hvilke gevinster
man kan høste ved en "databaseret" løsningstilgang. Derudover gør man sig
sårbar overfor det problem, der er i at historiske data repræsenterer bestemte 
aspekter af de observationer de repræsenterer og selv om observationerne ville
kunne bruges til at skabe en forbedret data-baseret process, så er det ikke
sikkert at data fra observationerne har været optaget med tilstrækkelig frekvens
eller de kan på anden vis være utilstrækkelige.

## Hvad med GenAI?!

_her forstået som de store sprogmodeller der kan imiterer skriftlig
kommunikation på et højt niveau eller danne billeder, lyd eller video_

Se på det som en ny mulighed der er kommet ud af grundforskning. Ligesom
laseren, velcro eller pencilin, vi skal finde ud af hvor det er smart at
anvende, hvilke opgaver de løser godt og på hvilket niveau.

## Hvad med revolutionen?!

Det den data baserede løsning/process kan bidrage med er i høj grad "bare"
optimering.

Den store _IDÉ_ - eureka-øjeblikket - kan komme på alle niveauer, men at få den
implementeret, så revolutionen faktisk kommer kræver at alle funktionerne 
spiller sammen. Og man kan ikke "bestille/ansætte" en revolution. Det kræver en
masse kendsskab, inspiration og så en tilfældig (men vil det vise sig) god idé.
