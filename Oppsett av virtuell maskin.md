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

<img width="470" height="310" alt="image" src="https://github.com/user-attachments/assets/4ed24f3a-5f56-4257-9b84-ef3957e907d0" />



---

## Steg 2 – Opprett ny virtuell maskin

I Hyper-V Manager, klikk på **Action** i menyen øverst → velg **New** → klikk på **Virtual Machine...**

<img width="510" height="315" alt="image" src="https://github.com/user-attachments/assets/0bca853d-907f-422a-b3fe-f53c8084a344" />




---

## Steg 3 – Start New Virtual Machine Wizard

Veiviseren åpnes med siden **Before You Begin**. Les gjennom informasjonen og klikk **Next** for å fortsette.

<img width="474" height="306" alt="image" src="https://github.com/user-attachments/assets/95e6c431-6e15-4679-80d6-9f33ff71f5f3" />




---

## Steg 4 – Gi VM-en navn og velg plassering

Skriv inn et navn på den virtuelle maskinen, f.eks. `Windows 11`.  
Velg hvor VM-filene skal lagres, f.eks.:

```
D:\VM\Windows 11
```

Klikk **Next** når du er ferdig.

>  Bruk et navn som gjenspeiler gjestens operativsystem for enkel identifikasjon.

<img width="474" height="306" alt="image" src="https://github.com/user-attachments/assets/a7a44fed-6413-4f40-b9b1-1927d48274ce" />



---

## Steg 5 – Velg generasjon

Velg **Generation 2** for moderne operativsystemer (støtter UEFI og 64-bit).  
Klikk **Next**.

>  **Merk:** Generasjon kan **ikke** endres etter at VM-en er opprettet.

<img width="512" height="273" alt="image" src="https://github.com/user-attachments/assets/51d4f476-449a-4f0f-b511-32a28623e0e2" />





---

## Steg 6 – Tildel minne

Sett **Startup memory** til ønsket verdi. Anbefalt for Windows 11:

```
4096 MB
```

Du kan også aktivere **Dynamic Memory** for automatisk minnejustering.  
Klikk **Next**.

<img width="484" height="260" alt="image" src="https://github.com/user-attachments/assets/4424cc32-7052-4456-8deb-5068d3c9c1e0" />




---

## Steg 7 – Velg nettverkstilkobling

Velg en nettverksadapter fra nedtrekkslisten.  
Velg **Default Switch** for enkel internettilgang uten ekstra konfigurasjon.  
Klikk **Next**.

<img width="474" height="270" alt="image" src="https://github.com/user-attachments/assets/55ff8418-e955-4865-a308-206584d14453" />



---

## Steg 8 – Opprett virtuell harddisk

Velg **Create a virtual hard disk** og angi:

- **Navn:** `Windows 11.vhdx`
- **Plassering:** `D:\VM\Windows 11\Virtual Hard Disks\`
- **Størrelse:** `60 GB` *(maks: 64 TB)*

Klikk **Next**.

>  VHDX-format brukes — dynamisk ekspanderende, noe som sparer diskplass.

<img width="498" height="273" alt="image" src="https://github.com/user-attachments/assets/d3723aad-d7be-482e-8816-f09d381e131f" />



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

<img width="476" height="270" alt="image" src="https://github.com/user-attachments/assets/02a42beb-a4c9-438c-8ef4-0406c15f9d81" />


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



