#  Opprette virtuell maskin i Hyper-V

> Steg-for-steg veiledning for å sette opp en virtuell maskin i Hyper-V Manager på Windows.

---

##  Krav

- Windows 10/11 Pro, Enterprise eller Education
- Hyper-V aktivert i Windows-funksjoner
- Minimum 4 GB RAM anbefalt
- Ledig diskplass til VM-en

---

## Steg 1 – Åpne Hyper-V Manager

Trykk på **Windows-tasten** og søk etter `hyper`. Velg **Hyper-V Manager** fra søkeresultatene.

<img 


---

## Steg 2 – Opprett ny virtuell maskin

I Hyper-V Manager, klikk på **Action** i menyen øverst → velg **New** → klikk på **Virtual Machine...**

<img 



---

## Steg 3 – Start New Virtual Machine Wizard

Veiviseren åpnes med siden **Before You Begin**. Les gjennom informasjonen og klikk **Next** for å fortsette.

<img 



---

## Steg 4 – Gi VM-en navn og velg plassering

Skriv inn et navn på den virtuelle maskinen, f.eks. `Windows 11`.  
Velg hvor VM-filene skal lagres, f.eks.:

```
D:\VM\Windows 11
```

Klikk **Next** når du er ferdig.

>  Bruk et navn som gjenspeiler gjestens operativsystem for enkel identifikasjon.

<img 


---

## Steg 5 – Velg generasjon

Velg **Generation 2** for moderne operativsystemer (støtter UEFI og 64-bit).  
Klikk **Next**.

>  **Merk:** Generasjon kan **ikke** endres etter at VM-en er opprettet.

<img 




---

## Steg 6 – Tildel minne

Sett **Startup memory** til ønsket verdi. Anbefalt for Windows 11:

```
4096 MB
```

Du kan også aktivere **Dynamic Memory** for automatisk minnejustering.  
Klikk **Next**.

<img 



---

## Steg 7 – Velg nettverkstilkobling

Velg en nettverksadapter fra nedtrekkslisten.  
Velg **Default Switch** for enkel internettilgang uten ekstra konfigurasjon.  
Klikk **Next**.

<img 


---

## Steg 8 – Opprett virtuell harddisk

Velg **Create a virtual hard disk** og angi:

- **Navn:** `Windows 11.vhdx`
- **Plassering:** `D:\VM\Windows 11\Virtual Hard Disks\`
- **Størrelse:** `60 GB` *(maks: 64 TB)*

Klikk **Next**.

>  VHDX-format brukes — dynamisk ekspanderende, noe som sparer diskplass.

<img 


---

## Steg 9 – Oppsummering og fullfør

Se gjennom oppsummeringen og bekreft innstillingene:

| Innstilling | Verdi |
|---|---|
| Navn | Windows 11 |
| Generasjon | Generation 2 |
| Minne | 4096 MB |
| Nettverk | Default Switch |
| Harddisk | Windows 11.vhdx (VHDX, dynamisk) |
| OS | Installeres fra ISO-fil |

Klikk **Finish** for å opprette VM-en.

>  Husk å koble til en ISO-fil etterpå for å installere operativsystemet.

<img 

---

##  Mappestruktur

```
repo/
├── README.md
└── bilder/
    ├── steg1.png
    ├── steg2.png
    ├── steg3.png
    ├── steg4.png
    ├── steg5.png
    ├── steg6.png
    ├── steg7.png
    ├── steg8.png
    └── steg9.png
``



