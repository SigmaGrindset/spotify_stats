ESH - extended streaming history


TOP PJESME, ALBUMI, ARTISTI, GENRES
- najvaznija statistika

1) sortiranje - sve ima ulazno/silaznu opciju
  - broj streamova - default - stream za pjesmu se broji ako je poslusano barem 30 sekundi pjesme
    - pjesma
    - album - koliko si pjesama s albuma streamao
    - artist - koliko pjesama od artista je streamao
    - genre - nije jasno moze li se dobiti genre za track ili samo za artista
            - ako se mogu vidjeti samo genres artista, onda svi streamovi pjesama od artista koji imaju specificni zanr,
              npr. svi artista koji imaju rap na listi zanrova. Zbrojiti koliko puta si streamao svakog od tih artista i rangirati po tome.
            - ako se moze vidjeti zanr specificne pjesme, onda broj streamova svih pjesama koje su tog zanra


  - minutes listened to - ESH
    - pjesma - koliko si vremena slusao pjesmu
    - album - koliko vremena slusao pjesme sa albuma
    - artist - koliko vremena slusao pjesme artista
    - genre - vidjeti ovisno o tome moze li se dobiti genre specificne pjesme ili samo genres artista
            - ako se mogu vidjeti samo genres artista, onda svo vrijeme koje si slusao pjesme od artista koja imaju specificni zanr,
              npr. svi artista koji imaju rap na listi zanrova. Zbrojiti vrijeme koje si slusao svakog od tih artista i rangirati po tome.
            - ako se moze vidjeti zanr specificne pjesme, onda vrijeme slusanja svih pjesama koje su tog zanra

  - popularity
    - artist
    - album
    - track

  - date released
    - pjesma - release date albuma na kojoj je pjesma
    - album - release date albuma

  - followers
    - artist - broj followera koje artist ima

  - total tracks
    - album

  - length
    - pjesma
    - album


2) vrijeme
  - zadnjih 1 tjedan
  - 1 mjesec
  - 3 mjeseca
  - 6 mjeseci
  - 1 godina
  - all time

ako nije importan ESH, moze prikazati albume, artiste, pjesme i genres?, u 3 vremenska perioda,
a moze sortirati po sve osim streams i minutes




RANDOM STATS
- fun stats za albume, artiste, pjesme i zanrove
- poanta je da pruza neke dodatne i zanimljive statistike, osim top albuma, artista....
- uzima u obzir samo iteme koji su "odabrani", dakle neki od top itema(artist, albumi....) u nekom time periodu (month,....)

1) albumi
  - za sve albume koje si sluzao, pokazati distribuciju kolicine pjesama / duljine u minutama
    - stupicasti graf: x-os kolicina pjesama na albumu, y-os broj albuma s tom kolicinom pjesama
    - potencijalno dobra ideja, ali pitanje je koje albume ukljuciti, a koje ne? -> mozda kasnije dodati
      - ocigledno ne zelim ukljuciti album s kojeg sam poslusao samo jednu pjesmu
      - pitanje se onda postavlja: kako odrediti koji je album "ciljno" poslusan?
      - mogu ukljuciti album - npr. ako si poslusao barem pola pjesama s albuma
      - bolje ako si poslusao svaku pjesmu s albuma barem jednom !!!

2) artist
                                                                           

3) track
  - na neki nacin prikazati distribucija duljine pjesama
    - Npr. stupicasti graf u kojem ce na x-osi biti brojevi 1,2,3.... koji ce biti intervali u trajanju minuta, a na y-osi
      broj pjesama koje su u tom intervalu
    - preslikavanje duljine u x-os : duljinu pjesmu u minuta zaokruziti gore, npr 1.5 minuta-> 2 minute....

  - distribucija desetljeca - isto kao iznad samo na x-osi desetljeca, a y-os koliko pjesama je iz tog desetljeca

  - explicit(yes/no) - koliki je dio explicit, a koliki nije

  - audio features - grupirati ih negdje
    - range 0-1 - acousticness, danceability, energy, instrumentalness, loudness, liveness, speechiness, valence
      - speechiness - ima kategorije - procitati api doc - vjerojatno samo prikazati kao range
    - tempo
    - mozda za svaki od ovih dodati graf kako se krecu iz godine u godinu - MOZDA

4) genres
  - popularity ako se moze dobiti ?

- Distribucija kada tijekom dana slusas pjesme, x-os: 0-24, y-os: koliko si pjesams poslusao u tom intervalu od sat vremena
  - ako je na nekom od top artist, track... screenova djeluje kao sve ostale fun statistike (isti time period)
  - inace bi bilo dobro dodati odabir intervala za ovaj graf specificno

- Svi prijasnji spotify wrappeds




MOJ WRAPPED
- experience
- animirano
- mozda video/audio pjesama koje su na njemu
- apple macbook stranica type shit






ACCOUNTS
- auth preko spotify api-a
- user ce biti ulogiran u svoj spotify account, ali morati cu taj account povezati sa DB
- dakle user nikada ne pravi svoj account specificno za stranicu, koristi spotify account

1) settings
  - light mode ? tesko testo
  - vise mogucih color schemova (vise opcija za primary color) ?













