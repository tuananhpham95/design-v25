---
Title: Laddningstider
Description: Analys av webbplatsers laddningstider
Template: analysis
---

# Laddningstider

=======================

Denna rapport utvärderar laddningstid och användbarhet på tre utvalda webbplatser, med fokus på hur dessa faktorer påverkar användarupplevelsen.

## Urval

Jag har valt följande webbplatser för analys:

- **Apple**[](https://www.apple.com): Valdes för att representera en premiumteknologiföretag med fokus på minimalistisk design och högkvalitativa produkter.
- **Spotify**[](https://www.spotify.com): Valdes för att representera en modern musikströmningstjänst med en dynamisk och användarcentrerad design.
- **Blekinge Tekniska Högskola (BTH)**[](https://www.bth.se): Valdes för att representera en akademisk institution med ett fokus på utbildning och forskning.

Urvalet gjordes medvetet för att jämföra webbplatser från olika kategorier: en kommersiell teknologiplattform (Apple), en tjänstebaserad underhållingsplattform (Spotify), och en offentlig utbildningsinstitution (BTH). Detta gör det möjligt att analysera hur laddningstid och användbarhet anpassas till olika målgrupper och syften.

## Metod

Jag använde Google PageSpeed Insights[](https://pagespeed.web.dev/) för att mäta laddningstid och användbarhet på Mobile och Desktop för tre sidor per webbplats. Mätningarna inkluderar Performance, Accessibility, Best Practices och SEO. För ytterligare mätningar använde jag Chrome DevTools i Network-fliken med shift+ctrl+r för att undvika cache, där jag noterade laddningstid, antal resurser och total storlek, med tre upprepningar per sida för att ta snittet. Alla mätningar dokumenterades i ett Google Sheets-ark.

## Resultat

Mätningarna finns i mitt Google Sheets-ark: [Länk till Excel-ark](https://docs.google.com/spreadsheets/d/e/2PACX-1vTsC2Nmq3hJ8VUV4VeHPcLOZ-CoY1xoKmwGD7ZN7plmu-7-AsO5YSVecsqvRv-En9Mkf-9a0dHz96Ju/pubhtml).

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTsC2Nmq3hJ8VUV4VeHPcLOZ-CoY1xoKmwGD7ZN7plmu-7-AsO5YSVecsqvRv-En9Mkf-9a0dHz96Ju/pubhtml?widget=true&amp;headers=false" width="1200" height="470" class="load-data"></iframe>

##### Apple[](https://www.apple.com)

- **Snapshot**: ![Snapshot of Apple](%assets_url%/img/apple-logo.jpg){.snapshot}
- **Sidor som mättes**:
  - https://www.apple.com (Home)
  - https://www.apple.com/iphone/
  - https://www.apple.com/watch/
- **Google PageSpeed**:
  - **Home[](https://www.apple.com)**:
    - Mobile: Performance [56], Accessibility [97], Best Practices [100], SEO [92]
    - Desktop: Performance [72], Accessibility [90], Best Practices [100], SEO [92]
  - **iPhone[](https://www.apple.com/iphone/)**:
    - Mobile: Performance [43], Accessibility [91], Best Practices [100], SEO [92]
    - Desktop: Performance [80], Accessibility [90], Best Practices [100], SEO [92]
  - **Watch[](https://www.apple.com/watch/)**:
    - Mobile: Performance [46], Accessibility [90], Best Practices [100], SEO [92]
    - Desktop: Performance [81], Accessibility [93], Best Practices [100], SEO [92]
  - Förbättringar: Reducera oanvänd JavaScript, optimera bilder.
- **Devtools-mätningar (genomsnitt av 3)**:
  - Home: Laddningstid [1.43s], Resurser [62], Storlek [9.3MB]
  - iPhone: Laddningstid [1.41s], Resurser [60], Storlek [6.3MB]
  - Watch: Laddningstid [1.33s], Resurser [49], Storlek [4.4MB]
- **Förbättringar**: Apple kan optimera bilder och reducera oanvänd JavaScript eller resurser på alla sidor för att minska laddningstider och storlekar, samt förbättra Mobile Performance genom att komprimera bildstorlekar och förbättra mobilrendering.

##### Spotify[](https://www.spotify.com)

- **Snapshot**: ![Snapshot of Spotify](%assets_url%/img/spotify-logo.png){.snapshot}
- **Sidor som mättes**:
  - https://www.spotify.com (Home)
  - https://www.spotify.com/premium/
  - https://www.spotify.com/download/
- **Google PageSpeed**:
  - **Home[](https://www.spotify.com)**:
    - Mobile: Performance [31], Accessibility [95], Best Practices [96], SEO [100]
    - Desktop: Performance [3], Accessibility [82], Best Practices [96], SEO [100]
  - **Premium[](https://www.spotify.com/premium/)**:
    - Mobile: Performance [45], Accessibility [96], Best Practices [100], SEO [92]
    - Desktop: Performance [62], Accessibility [96], Best Practices [100], SEO [92]
  - **Download[](https://www.spotify.com/download/)**:
    - Mobile: Performance [56], Accessibility [96], Best Practices [82], SEO [100]
    - Desktop: Performance [74], Accessibility [96], Best Practices [81], SEO [100]
  - Förbättringar: Optimera bilder, minska JavaScript-utförningstid.
- **Devtools-mätningar (genomsnitt av 3)**:
  - Home: Laddningstid [12.5s], Resurser [208], Storlek [16.3MB]
  - Premium: Laddningstid [6.1s], Resurser [146], Storlek [8.0MB]
  - Download: Laddningstid [6.3s], Resurser [109], Storlek [7.2MB]
- **Förbättringar**: Spotify kan optimera bilder och minska antalet resurser eller JavaScript-utförningstid på alla sidor för att sänka laddningstider och storlekar, samt förbättra Mobile Performance genom att komprimera bildfiler och lazy-load icke-kritiska skript.

##### Blekinge Tekniska Högskola (BTH)[](https://www.bth.se)

- **Snapshot**: ![Snapshot of BTH](%assets_url%/img/bth-logo.png){.snapshot}
- **Sidor som mättes**:
  - https://www.bth.se (Home)
  - https://www.bth.se/utbildning/
  - https://www.bth.se/forskning/
- **Google PageSpeed**:
  - **Home[](https://www.bth.se)**:
    - Mobile: Performance [56], Accessibility [93], Best Practices [82], SEO [92]
    - Desktop: Performance [76], Accessibility [100], Best Practices [100], SEO [92]
  - **Utbildning[](https://www.bth.se/utbildning/)**:
    - Mobile: Performance [57], Accessibility [100], Best Practices [100], SEO [85]
    - Desktop: Performance [77], Accessibility [100], Best Practices [100], SEO [85]
  - **Forskning[](https://www.bth.se/forskning/)**:
    - Mobile: Performance [68], Accessibility [92], Best Practices [100], SEO [85]
    - Desktop: Performance [92], Accessibility [100], Best Practices [100], SEO [85]
  - Förbättringar: Reducera oanvänd CSS, optimera bilder, förbättra tillgänglighet.
- **Devtools-mätningar (genomsnitt av 3)**:
  - Home: Laddningstid [6.25s], Resurser [92], Storlek [7.4MB]
  - Utbildning: Laddningstid [6.20s], Resurser [71], Storlek [5.9MB]
  - Forskning: Laddningstid [6.01s], Resurser [75], Storlek [5.9MB]
- **Förbättringar**: BTH kan optimera bilder och reducera oanvänd CSS eller resurser på alla sidor för att förbättra laddningstider och Mobile Performance, genom att komprimera visuella element och rensa onödiga stilar."

## Analys

De vanligaste förbättringsåtgärderna i mitt urval är att optimera bilder och reducera oanvänd JavaScript eller CSS, vilket är särskilt tydligt för Spotify (låg Mobile Performance på 31 och laddningstid på 12.5s) och Apple (Mobile Performance varierar mellan 43-56). BTH visar också behov av optimering, med lägre Mobile Performance (58-62) och laddningstider runt 2.8-3.0s. Apple presterar bäst med höga Desktop-betyg (72-81) och korta laddningstider (1.33-1.43s), medan Spotify lider av stora resursstorlekar (upp till 16.3MB) och BTH har en balanserad men förbättringsbar prestanda på mobila enheter.

## Rangordning

1. Apple (högsta Desktop Performance 72-81, snabbaste laddningstid 1.33-1.43s).
2. BTH (balanserad Desktop Performance 78-82, laddningstid 2.8-3.0s).
3. Spotify (lägst Desktop Performance 3-74, längsta laddningstid 6.1-12.5s).

Vinnaren är Apple, som visar att minimalistisk design och effektiv resursanvändning leder till överlägsen prestanda, medan Spotify behöver adressera sin höga laddningstid och BTH kan förbättra mobilupplevelsen.

## Gränsvärde för laddningstid

Jag definierar en snabb webbplats som laddar under 2s. Apple klarar detta på alla sidor (1.33s-1.43s), BTH är nära men över gränsen (2.8s-3.0s), och Spotify överstiger tydligt gränsen (6.1s-12.5s). Generellt upplever jag Apple som mycket snabb, BTH som acceptabel men något seg, och Spotify som trög, särskilt på Home-sidan, vilket påverkar användarupplevelsen negativt.

## Övrigt

Rapport skriven av: [Tuan Anh Pham].
