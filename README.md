# latex-gdpr-template

Latex reimplementation af Aarhus Universitet's GDPR dokumenter

## Brug af GDPR-skabeloner

Filen `GDPR-template.tex` er den primære GDPR blanket som deltagere af studiet/evalueringen/eksperimentet skal underskrive. Alle nødvendige ændringer sker øverst i dokumentet.

Filen `Fortegnelse_over_behandling_af_behandlingsaktiviteter.tex`  Er en oversigt over de hvilke aktiviteter indsamlet data indgår i og med hvem det bliver delt med. Udfyld variabler øverst i dokumentet for at tilpasse dokumentet.
Dokument er nødvendigt for 1-persons projekter. 

Filen `Fælles_dataansvar.tex`  udgør en aftale mellem gruppens medlemmer over det fælles dataansvar, og hvem der har specifikt ansvar for bestemte underaktiviteter. Udfyld variabler øverst i dokumentet for at tilpasse dokumentet. Modsat de andre dokumenter skal der her specificeres hvor mange personer der er i gruppen, for at tabellen med svarsområder kan opbygges korrekt. 

**Bemærk**: Hvis ansvar er fordelt bland flere studerende end der er i gruppen vil disse ansvar ikke blive skrevet ind i tabellen, og rækken vil i stedet vil fremstå tom.  

Dette dokument er ikke nødvendigt for 1-persons projekter, da det er implicit at alt ansvar ligger hos den ene person. 

## Roadmap

- [ ] Få AU til at bruge de her template i stedet for deres forfærdelige Word skabeloner
- [x] Fælles dataansvar programmeret til at tilpasse layout til antal gruppemedlemmer (2-4). 
- [x] Variabel-baseret redigering af tabeller i `fortegnelse af behandlingsaktiviteter` og `fælles dataansvar` dokumenter
- [x] Dato som variable i tilfælde af at dokumenter skal benyttes på en anden dato end udskriftsdagen.
