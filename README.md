# Rapport – Active Directory og PowerShell Gruppe
Navn: Zaid
Dato: 24.04.2026
Fag: AD_PowerShell_spring_2026


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



Skjermbilder:

<img width="426" height="223" alt="image" src="https://github.com/user-attachments/assets/6652e50f-84c5-4fb0-bc83-4d075da0550d" />
## Skjermbilde: 2
<img width="514" height="278" alt="image" src="https://github.com/user-attachments/assets/db32242e-a1a2-4743-a258-c49f9986646d" />
## Skermbilde: 3
<img width="452" height="276" alt="image" src="https://github.com/user-attachments/assets/d61ad792-8342-485a-a0da-df5900a9c586" />
## Skjermbilde: 4
<img width="404" height="342" alt="image" src="https://github.com/user-attachments/assets/13a607a2-cfde-4212-a12e-0d46b48fbd1b" />
## Skermbilde: 5
<img width="522" height="220" alt="image" src="https://github.com/user-attachments/assets/d6ebbf49-8031-4d8c-ac83-0aeacab4c2c6" />
## Skjermbilde: 6
<img width="502" height="402" alt="image" src="https://github.com/user-attachments/assets/24b3affa-1bc0-471d-bc09-a1a016acbf95" />
## Skjermbilde: 7
<img width="438" height="328" alt="image" src="https://github.com/user-attachments/assets/e02c81ba-14dc-42b9-bb12-1c6b68563a03" />
## Skjermbilde 8
<img width="438" height="328" alt="image" src="https://github.com/user-attachments/assets/611a23fe-d131-450c-8991-269c2d393442" />





