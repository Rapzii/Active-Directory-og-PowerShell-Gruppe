# Rapport – Active Directory og PowerShell Gruppe
Navn: Zaid
Dato: 24.04.2026
Fag: AD_PowerShell_spring_2026

Innledning
I denne oppgaven har jeg jobbet med Active Directory og PowerShell. Målet var å lære hvordan man kan administrere brukere, grupper og datamaskiner i et domene. Jeg fikk også erfaring med hvordan PowerShell kan brukes til å gjøre oppgaver raskere og enklere.
Arbeid med Active Directory
Jeg brukte Active Directory Users and Computers for å opprette en struktur med ulike OU-er (Organizational Units). Jeg lagde egne mapper for:
Elever
Undervisere
Ledelse
Under Elever ble det laget flere undergrupper for klassetrinnene 1 til 7. Dette gjør det lettere å holde orden på brukerne og plassere dem riktig.
Jeg opprettet også brukere og grupper som kunne brukes til tilgangsstyring.
Group Policy
Jeg jobbet med Group Policy Management og opprettet GPO-er som ble koblet til de ulike OU-ene. Der satte jeg opp:
Fast bakgrunnsbilde
Skjermsparer
Skjermsparer etter 5 minutter
Passord når skjermsparer avsluttes
Dette viser hvordan man kan styre mange PC-er samtidig fra serveren.
PowerShell
Jeg brukte også PowerShell for å administrere Active Directory. Det er nyttig fordi man kan automatisere oppgaver i stedet for å gjøre alt manuelt.
Eksempel på kommandoer jeg jobbet med:

## Viser alle brukere i domenet.
Get-ADGroup -Filter *

## Viser alle grupper.
New-ADUser -Name "Testbruker"
Lager en ny bruker.

# Hva jeg lærte
Jeg lærte hvordan Active Directory brukes i bedrifter og skoler for å organisere brukere og datamaskiner. Jeg lærte også at PowerShell er et kraftig verktøy som gjør administrasjon raskere.
Det viktigste jeg lærte var:
Lage OU-struktur
Opprette brukere og grupper
Bruke GPO
Bruke PowerShell-kommandoer
Tilgangsstyring med grupper
Konklusjon
Denne oppgaven ga meg bedre forståelse av hvordan Windows Server og Active Directory fungerer. Jeg synes det var nyttig å lære PowerShell siden det sparer tid og brukes mye i IT-yrker. Dette er kunnskap jeg kan få bruk for senere innen IT-drift og support.
