---
layout: page
title: Hjem
permalink: /hjem/
nav_order: 1
---

# Mystore Datakasse dokumentasjon (v 4.0.2)
{: .no_toc }
Velkommen til dokumetasjonen for Mystore Datakasse. Du kan navigere til ønsket emne i sidemenyen,<br> eller benytte deg av søkefeltet øverst på siden. 

Under har vi også listet opp forklaring på de forskjellige sidene/skjermene i Mystore Datakasse.

Finner du ikke svar på spørsmålet ditt? [Ta kontakt med Mystore Kundeservice](https://www.mystore.no/kontakt-oss) 

--- 

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Hjem/forside
![hjem](/pos-doc/assets/images/dokumentasjon_index_page.jpg)

1. [Hovedmeny](https://mystoreno.github.io/pos-doc/hjem/#h)
2. Åpner søkefeltet
3. Viser valgt selger/bruker. Trykk på navnet for å åpne selgermenyen
4. Ikon for bankterminal. Denne lyser grønt når terminal er koblet til. Trykk på ikonet for å gå til terminalinnstillinger
5. Viser valgt kunde. Trykk på navn/ikon for å velge kunde, eller for å legge til ny kunde. Standard valg er sluttkunde/kontantkunde
6. Merker/produsenter
7. [Kategorivalg](https://mystoreno.github.io/pos-doc/hjem/#kategorivalg). Her kan du velge favorittkategorier (se også punkt 11) og bestemme visning av kategorier
8. Legg til genereisk produkt (diverseprodukt) eller gavekort via denne knappen
9. Sett rabatt i prosent for hele handlekurven
10. Tøm hele handlekurven
11. [Favorittkategorier](https://mystoreno.github.io/pos-doc/hjem/#kategorivalg). Hvis du har kategorier som du raskt vil navigere til (se også punkt 7)
12. Utvalgte produkter/favorittprodukter. Settes via _produktinfo_ i produktboksene
13. Kategorier
14. Betalingsmetoder

## Kategoriside
![kategoriside](/pos-doc/assets/images/dokumentasjon_kategori.jpg)

{: .highlight }
Trykk på produktboks (bilde/tittel/pris) for å legge produkt til handlekurv

1. Hjemikon. Tar deg til forsiden
2. Tilbakepil. Tar deg ett steg tibake
3. _Breadcrumb_. Viser hvor du er i kategoristrukturen. Kategorinavnene kan trykkes på for rask navigering
4. Produktnavn
5. Produktets pris
6. Åpner produktinformasjon

### Produktinformasjon
![produktinfo](/pos-doc/assets/images/dokumentasjon_produktinfo_ny.jpg)

1. Favorittstjerne. Marker for å sette produktet som favoritt/utvalgt produkt. Produktet vil da vises på forsiden over kategoriene (se [Hjem/forside][https://mystoreno.github.io/pos-doc/hjem/#hjemforside) punkt 12)
2. Produktdata hentet fra produktkortet i kontrollpanelet (pris, avanse, produsent, artikkelnummer, EAN, Lagerlokasjon og lagerbeholdning) 
3. Hvis produkter har vatrianter vil disse vises i en tabell med tilhørende produktdata (lager, art nr, lagerlokasjon hvis spesifisert og EAN). Du har også en fane for produktbeskrivelse og produktegenskaper hvis dette er lagt inn på produktet

{: .highlight }
Feltene _Innpris_ og _Avanse_ kan skjules/aktiveres i kontrollpanelet via **Konfigurasjon > Generelt > POS > _Vis bruttofortjeneste_**

## Hovedmeny
![hovedmeny_1](/pos-doc/assets/images/dokumentasjon_hovedmeny_1.jpg)

1. Åpner [innstillinger](https://mystoreno.github.io/pos-doc/hjem/#innstillinger)
2. Start kassasalg/sesjon
3. Viser omsetning på nåværende sesjon. Kan også skrives ut
4. Trykk her for å koble til eller sjekke tilkoblingsstatus på kvitteringsskriver 
5. Åpner en [liste/meny med siste ordrer](https://mystoreno.github.io/pos-doc/hjem/#siste-ordrer) fra alle kassapunkter, refusjoner (til bankkort) og ordrer fra nettbutikk
6. Trykk her for å søke opp ordre
7. Skriver ut siste kvittering (hvis kvitteringsskriver er tilkoblet)
8. Åpner kassaskuffen hvis tilkoblet
9. Trykk her for å logge ut. Navn i parentes viser innlogget bruker
10. Viser kasse ID. [Les mer](https://mystoreno.github.io/pos-doc/kom-i-gang/kassapunkter/)
11. Butikknavn/adresse
12. Versjon av Mystore Datakasse
![hovedmeny_2](/pos-doc/assets/images/dokumentasjon_hovedmeny_2.jpg)
13. Stopp kassasalg/sesjon (oppgjør/avstemming)
14. Viser ID til nåværende sesjon (z-rapport)

## Innstillinger
### Generelt
![innstillinger_generelt](/pos-doc/assets/images/dokumentasjon_innstillinger_generelt_ny.jpg)

1. Gir deg en advarsel his produktet du legger i handlekurven har 0 eller
negativ lagersaldo (disponibelt lager). Du kan så velge om du vil avbryte salget eller fortsette 
2. Med denne skrudd på vil selgermenyen automatisk åpnes etter fullført salg/ordre. Eventuelt modalen for ansattkort/PIN-kode (punkt 3), hvis denne er aktivert
3. Selger velges med scanning av ansattkort eller PIN-kode
4. Lar deg sette utløpsdato på byttelappene. Du kan enten skrive inn antall dager, eller velge en spesifikk dato.

### Skriver
![innstillinger_generelt](/pos-doc/assets/images/dokumentasjon_innstilinger_skriver.jpg)

1. Lar deg koble til kvitteringsskriver
2. Skru denne på hvis du ønsker automatisk utskrift av kvittering etter hvert salg. Skriver må være tilkoblet

### Betaling
![innstillinger_betaling](/pos-doc/assets/images/dokumentasjon_innstilinger_betaling.jpg)

1. Åpner [terminalinnstillinger hvor du kan koble til, koble fra eller endre bankterminal](https://mystoreno.github.io/pos-doc/kom-i-gang/bankterminal/)
2. Hvis du vil tilby kundene å dele opp betalingen på flere bankkort, eller dele mellom bankkort og vipps 
3. Kontantbetaling må være på skrudd for å kunne ta i mot kontanter. Hvis denne slås av forsvinner **Kontant** fra betalingsmetoder. Hvis du har kassaskuff koblet til kassasystemet vil skuffen åpnes automatisk når ordren slås ut på betalingsmetode **Kontant**
4. Ønsket kontantbeholdning ved oppstart/avslutning. Beløpet settes i kontrollpanelet via Konfigurasjon > Generelt > POS

### Visning
![innstillinger_visning](/pos-doc/assets/images/dokumentasjon_innstilinger_visning.jpg)

1. Aktiverer selvbetjentmodus
2. Valg for å vise produktbilder i handlekurven 

### Annet
![innstillinger_annet](/pos-doc/assets/images/dokumentasjon_innstilinger_annet.jpg)

1. Analyseinformasjonen og statistikken er samlet i et format som ikke identifiserer deg personlig. Hensikten er å hjelpe Mystore med å forbedre produktet og tjenesten
2. Sletter data lagret lokalt i appen. Vi oppbevarer ingen bokførte opplysninger lokalt i appen. For å ivareta Kassasystemforskriften lagres alle opplysninger i butikkens kontrollpanel. Dette er lokalisert på [butikknavn].mystore4.no/kontrollpanel. Alle opplysninger er tilgjengelig i kontrollpanelet og til enhver tid tilgjengelig for butikkeier og eventuelt skatteetaten for kontroll
3. Her kan du sjekke status på din internettforbindelse

## Kategorivalg
![kategorivalg](/pos-doc/assets/images/dokumentasjon_kategorivalg.jpg)

1. Lukk kategorivalg
2. Tilbakestiller alle tilpassninger av kategorier og favoritter
3. Lukker kategorivalg (lagring skjer fortløpende)
4. Viser til at kategorien har flere nivåer (underkategori). Trykk på pilen for å gå til underkategori
5. Marker stjernen for å sette kategorien som favoritt
6. Bryteren/knappen bestemmer visning av kategorien i datakassen. Hvis du ønsker å skjule en kategori kan du slå av visningen her 

## Siste ordrer
![siste_ordrer](/pos-doc/assets/images/dokumentasjon_ordrer.jpg)

1. Viser siste ordrer fra kassen du behandler
2. Viser siste ordrer fra alle kassepunkt (hvis flere)
3. Viser siste ordrer fra nettbutikk (hvis du også har nettbutikk)
4. Viser siste refusjoner til bankkort
5. Åpner flere valg per ordre
6. Viser kvitteringen til ordren
7. Skriver ut kopi av kvittering (kvitteringsskriver må være tilkoblet)
8. Sender kopi av kvittering på SMS
9. Registrer retur/bytte på hele eller deler av ordren
10. Åpner valg for byttelapp. Skriv ut byttelapp for hele eller deler av ordren

## Søk opp ordre (for å registrere retur)
![order_search](/pos-doc/assets/images/dokumentasjon_search_order.jpg)

1. Felt for å skrive inn ordrenummer eller strekkoden nederst på fysisk kvittering
2. Lukker modalen

![order_search_2](/pos-doc/assets/images/dokumentasjon_search_order_2.jpg)

1. Ordrenummer
2. Kundenavn
3. Ordreinfo/data
4. Lukker modal og avbryter
5. Fortsett til [returbehandling](https://mystoreno.github.io/pos-doc/retur-bytte-reklamasjon/) av gitt ordre
















