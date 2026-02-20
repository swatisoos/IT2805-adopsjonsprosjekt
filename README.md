# IT2805 – Adopsjonsprosjekt (Frontend)

Dette prosjektet ble utviklet som en del av faget **IT2805 – Webteknologi** ved NTNU.  
Målet var å lage en komplett, responsiv nettside for en fiktiv hundeadopsjonstjeneste – med fokus på HTML, CSS og JavaScript.

Prosjektet består av flere undersider, komponenter og dynamiske funksjoner bygget uten rammeverk, kun ren frontend-kode.

---

## Funksjonalitet

### Hjemside
- Presentasjon av organisasjonen  
- Dynamiske "steg-kort" generert via JavaScript  
  (se `createHomePageCard.js` :contentReference[oaicite:0]{index=0})

### Om oss
- To seksjoner med tekst og bilder  
- Bruker gjenbrukbar navbar og footer komponert med JS  
  (se `nav.js` :contentReference[oaicite:1]{index=1} og `footer.js` :contentReference[oaicite:2]{index=2})

### Hundeliste (Dogs)
- Viser alle hunder tilgjengelig for adopsjon  
- Hundene genereres dynamisk fra et data-array  
  (se `allDogs.js` :contentReference[oaicite:3]{index=3})
- Klikk på en hund → åpner individuell hundeside

### Hundeside (DogNPage)
- Viser bilde, tekst og informasjon for valgt hund  
- Data sendes via `localStorage`  
- Adopsjonsskjema som vises ved knappetrykk  
  (se `adoptionform.js` :contentReference[oaicite:4]{index=4})

### 🔹 Donasjonsside
- Informasjon om støtteordninger  
- Responsiv CSS med flere layout-tilpasninger  
  (se `Donate.html` :contentReference[oaicite:5]{index=5})

---

## Design & Struktur

### CSS
All styling ligger i én felles fil:  
`style.css` :contentReference[oaicite:6]{index=6}

Inkluderer:
- Responsiv navbar (landskap/portrett)
- Grid-basert footer
- Fleksible kort, bokser og seksjonskomponenter
- Layout for alle undersider

### JavaScript komponenter

| Fil | Rolle |
|-----|-------|
| `nav.js` :contentReference[oaicite:7]{index=7} | Dynamisk navbar injisert på alle sider |
| `hamburger.js` :contentReference[oaicite:8]{index=8} | Mobilmeny og vis/skjul-logikk |
| `footer.js` :contentReference[oaicite:9]{index=9} | Footer generert på alle sider |
| `allDogs.js` :contentReference[oaicite:10]{index=10} | Hundedata + generering av hundebokser og hundesider |
| `adoptionform.js` :contentReference[oaicite:11]{index=11} | Åpning/visning av adopsjonsskjema |
| `createHomePageCard.js` :contentReference[oaicite:12]{index=12} | Lager steg-kort på forsiden |

---

## Mappestruktur
style.css
/JS
nav.js
hamburger.js
footer.js
allDogs.js
createHomePageCard.js
adoptionform.js
/HTML
HomePage.html
AboutUs.html
Dogs.html
DogNPage.html
Donate.html
/images
(logoer og hundebilder)


---

## Kjøre prosjektet

Dette er et rent frontend-prosjekt.  
For å kjøre:

1. Last ned repoet
2. Åpne **HomePage.html** i en nettleser

Ingen installasjon, server eller rammeverk nødvendig.

---

## Forfatter
Swati Soosaipillai  
IT2805 – NTNU