---
layout: page
title: Start og stopp kassasalg
permalink: /kassasalg-start-stopp/
nav_order: 4
---

# Start og stopp kassasalg (sesjon)

## Start kassasalget
Før du kan selge varer må du starte en sesjon. En sesjon bør vare fra du starter dagen/kassen til du avslutter for dagen. <br>
Trykk _Hovedmeny > Start kassasalg_ for å starte kassasalget/sesjonen.
![start_kassasalg](/pos-doc/assets/images/sesjon_start.jpg)

## Stopp kassasalget 
1. For å avslutte sesjonen og ta oppgjør/avstemming trykker du _Hovedmeny > Stopp kassasalg_
![stopp_kassasalg](/pos-doc/assets/images/sesjon_stopp.jpg) <br>
2. Legg inn kontantbeholdning
![avstemming_2](/pos-doc/assets/images/oppgjor_2.jpg) <br>
3. Bekfreft opptalt kontantbeholdning, eller tell på nytt
![avstemming_3](/pos-doc/assets/images/oppgjor_3.jpg) <br>
4. Se over oppsummeringen og legg eventuelt inn uttak til bank/nattsafe, og/eller kommenter avstemmingen
5. Trykk _Fullfør avstemming_ 
![avstemming_4](/pos-doc/assets/images/oppgjor_4.jpg) <br>
6. Z-rapport skrives ut (hvis printer er tilkoblet) og sendes på e-post til butikkens registrerte e-postadresse. Denne ligger i kontrollpanelet (_Konfigurasjon > Generelt > E-post > Butikkens e-postadresse_) 

### Har du integrasjon mot Tripletex?
Med integrasjon mot Tripletex vil z-rapporten automatisk overføres når du fullfører avstemmingen. Oversikt/logg finner du i kontrollpanelet via _Verktøy > Automatisk regnskapsføring > Historikk_

## Z-rapporten forklart

- Firmananavn og org nr
- Sesjonsnummer/ID
- Fra dato (når sesjon ble startet)
- Til dato (når sesjon ble avsluttet og z-rapport generert)
- Oppsummering av transaksjoner fordelt på betalingsmetoder
- Spesifisering av solgte gavekort og hvilke betalingsmetoder som ble benyttet
- Oppsummering av returer og hvilke betalingsmetoder disse er slått ut på
- Summering omsetning inkl. mva. Gjeld (gavekort/tilgodelapp) vil her stå med minusfortegn da disse tranaksjonene ikke er omsetning
- Omsetning summert fordelt på varegupper. Her vil både momsgrunnlag og moms være spesifisert
- Summering av omsetning fordelt på mva
- Historisk oppsummering. Total summering av alle kassens salg og returer
- Oppsummering av bruk
  - Øreavrunding: Antalll øreavrundinger og total verdi
  - Antall bytter/returer: Alle bytter/returer registrert på sesjonen og total verdi av disse
  - Antall reklamasjoner: Antll returer/bytter som er spesifisert som reklamasjon. Disse varene legges da ikke tilbake på lager
  - Avbrutte salg: Viser til antall tilfeller handlekurven er tømt/slettet av ekspeditør, og total verdi av disse
  - Rabatter gitt: Antall rabatter og total verdi (eksl. mva) gitt i løpet av sesjonen
  - Salgskvitteringer: Viser til alle kvitteringer slått ut på ordrer med positiv totalsum. Antall og total verdi
  - Returkvitteringer: Viser til alle kvitteringer slått ut på ordrer med negativ totalsum. Antall og total verdi
  - Kvitteringskopier: Antall kvitteringskopier skrevet ut og total verdi. Denne tar for seg/regner sammen både vanlige salgskvitteringer og returkvitteringer
  - Korreksjoner (pris/prosent): Rabatter registrert direkte på varelinjer (ekskl. mva)
  - Kassaskuff åpnet: Antall ganger kassaskuffen er åpnet i løpet av sesjonen 
- Avstemming
  - Sum kontanter ved start: Kontantbeløp i vekselkasse registert av ekspeditør ved oppstart av sesjon/kassasalg
  - Sum kontanter ved avslutning: Kontantbeløp i vekselkasse registert av ekspeditør ved avslutning av sesjon/kassasalg
  - Differanse: Differanse mellom registrert kontantbeløp i vekselkasse og omsetning i kontanter på gitt sesjon
  - Uttak til bank/nattsafe: Beløp fra vekselkasse ekspeditør tar ut til bank/nattsafe
  - Ny saldo: Kontantbeløp som nå vil ligge i vekselkasse (etter uttak til bank/nattsafe)
-Signatur av ekspeditør som har utført avstemming/oppgjør 
