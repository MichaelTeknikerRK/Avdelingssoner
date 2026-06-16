# Hjemmetjenesten Mo i Rana – Avdelingsoversikt

Interaktivt kart over hjemmetjenestens avdelingssoner og omsorgsboliger i Rana Kommune. Designet for å printes ut som A4 liggende.

## 🗺️ Hva kartet viser

**6 avdelingssoner** (fargede polygoner):

| Farge | Avdeling |
|-------|----------|
| 🔴 Rød | Vest 1 |
| 🟠 Oransje | Sør |
| 🟡 Gul | Øst 1 |
| 🔵 Blå | Vest 3 |
| 🟢 Grønn | Nord |
| 🟣 Lilla | Sentrum 3 |

**10 omsorgsboliger** (numrerte prikker):

| Nr. | Navn | Avdeling |
|-----|------|----------|
| 1 | Gruben Bosenter | Øst 1 |
| 2 | Hauknes Omsorgsbolig | Sør |
| 3 | Mjølan Omsorgsbolig | Vest 3 |
| 4 | Mo Bo og Servicesenter | Øst 1 |
| 5 | Selfors Omsorgsbolig | Nord |
| 6 | Sentrumsgården Omsorgsbolig | Sentrum 3 |
| 7 | Talvikparken Bosenter | Nord |
| 8 | Utskarpen Bosenter | Vest 1 |
| 9 | Ytteren Bosenter | Vest 1 |
| 10 | Ytteren Omsorgsbolig | Vest 3 |

## 🖱️ Slik bruker du kartet

- **Zoom** med musescroll
- **Panorer** ved å klikke og dra
- **Filtrer** avdelinger og omsorgsboliger ved å klikke på elementene i footeren nederst
- Når du er fornøyd med utsnittet → trykk **🖨 Skriv ut** (vises kun i nettleser, ikke på print)

## 🚀 Deploy til GitHub Pages

### Steg 1 – Opprett repository

1. Gå til [github.com](https://github.com) og logg inn
2. Klikk **New repository**
3. Gi det et navn, f.eks. `avdelingsoversikt`
4. Sett det til **Public**
5. Klikk **Create repository**

### Steg 2 – Last opp filer

Last opp disse to filene til repositoriet:

- `index.html` ← **omdøp** `Avdelingsoversikt_MoiRana.html` til `index.html` før opplasting
- `README.md`

### Steg 3 – Aktiver GitHub Pages

1. Gå til **Settings** i repositoriet
2. Klikk **Pages** i venstremenyen
3. Under *Source* velger du **Deploy from a branch**
4. Velg branch: **main**, mappe: **/ (root)**
5. Klikk **Save**

### Steg 4 – Åpne lenken

Etter 1–2 minutter er kartet tilgjengelig på:

```
https://[ditt-brukernavn].github.io/[repo-navn]/
```

Eksempel:
```
https://ranakommune.github.io/avdelingsoversikt/
```

> **Tips:** Lenken finner du også under **Settings → Pages** når den er klar.

## 📁 Filer

```
index.html      Selve kartet (A4 liggende, interaktivt + printbart)
README.md       Denne filen
```

## 🛠️ Teknologi

- [Leaflet.js](https://leafletjs.com/) – kartbibliotek
- [CartoDB Positron](https://carto.com/basemaps/) – bakgrunnskart
- Sonegrenser basert på KML-eksport fra Google My Maps
- Adressekoordinater geocodet via OpenStreetMap / Nominatim

---

*Rana Kommune · Helse og omsorg · Hjemmetjenesten*
