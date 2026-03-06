# AMBA Pitch – Status & Kontekst
**Sidst opdateret:** 3. marts 2026  
**Præsentation:** `c:\AI\AMBA\index.html`  
**Preview:** `http://localhost:8080/index.html` (kør server med `python -m http.server 8080` i `C:\AI\AMBA`)

---

## Hvad er dette?

En single-file HTML5 pitch-præsentation til **Coop amba ledelsesmøde** om projektet **"Det Digitale Klubhus"** – en platform der aktiverer Coops 2 mio. medejere via 6 sammenhængende mekanikker bygget oven på eksisterende infrastruktur (QuickInfo, CoopApp, FB Board Templates).

**Bygherre:** QuickInfo (50% Coop-ejet, Karsten Toksvig er admin)  
**Pitch-modtager:** Coop amba ledelse

---

## Teknisk stack

- **Ét HTML-fil** – ingen dependencies udover CDN
- **Tailwind CSS** – `cdn.tailwindcss.com`
- **Lucide Icons** – `unpkg.com/lucide@latest/dist/umd/lucide.js`
- **Coop farver:** `--red: #DA291C`, `--anthracite: #111111`
- **Navigation:** Piletaster, Space, touch-swipe (>55px), dot-nav, progress bar

---

## Slide-struktur (11 slides, TOTAL=11)

| ID | Linje ca. | Titel / Indhold |
|---|---|---|
| `#slide-0` | ~197 | **Hook** – Sort skærm, fade-in: "Coop har 2 millioner medejere. I dag kender vi dem ikke." |
| `#slide-qi` | ~208 | **QuickInfo – Hvem er vi** – 6 KPI'er, 3 testimonials, Carsten Toksvig citat |
| `#slide-1` | ~274 | **Hero** – "Fra Medlem til Holdkammerat" + Board Templates pill-badges + factbox |
| `#slide-2` | ~336 | **Figma Prototype** – 4 CSS phone mockups (Opslagstavlen, Tilmelding, Skridt-log, Leaderboard) |
| `#slide-3` | ~381 | **De 6 Mekanikker** – 3×2 grid med interaktivt lykkehjul (hover-spin) |
| `#slide-4` | ~634 | **Case: Pilot-butik** – 3-trins flow + Figma leaderboard (Kvickly Åbyhøj) |
| `#slide-5` | ~728 | **Demokratisk Motor** – Flowpil + 3 mikro-afstemning eksempler |
| `#slide-6` | ~780 | **Loopet** – Flowdiagram + Board Templates proof strip (Karsten Toksvig session) |
| `#slide-7` | ~828 | **amba Dashboard** – KPI-kort, geo-aktivitet, aktive missions (MOCKUP DATA badge) |
| `#slide-8` | ~885 | **Tidslinje** – Mar→Apr→Maj→Jul 2026 + 3 objection handlers |
| `#slide-9` | ~925 | **CTA** – "Det Digitale Klubhus skal bygges. Men vi starter ikke fra nul." |

---

## Nøgle-narrativ (må ikke ændres)

> *"Det Digitale Klubhus skal bygges – men vi starter ikke fra nul. Fundamentet er allerede der."*

**Hvad der eksisterer i dag (amba har adgang nu):**
- **Board Templates** – ét admin-panel der poster til både CoopApp + 1.000+ FB-sider simultant
- **QuickSale Engine** – skridt, spin, auktion, voting er klar på quickinfo.dk
- **Figma-design** – klar til developer handoff

**Hvad der skal bygges:**
- Selve Det Digitale Klubhus (UX-lag, integrationer, eventuel ny backend-logik)

**Den stærkeste linje i decket:**
> *"Et medlem der gik 5.000 skridt for sin Kvickly sidst onsdag – skifter ikke til Netto om fredagen."*

---

## Vigtige detaljer & valg truffet

| Emne | Beslutning |
|---|---|
| Alle badges | Lilla `FIGMA PROTO` / `MOCKUP DATA` / `FIGMA` – IKKE grøn LIVE |
| Antal butikker | **1.000+** (ikke 1.200+) |
| Medejere | **2 millioner** |
| "Fra Kunde til" | Rettet til **"Fra Medlem til"** (kun medlemmer deltager) |
| "0 kr." på CTA | Fjernet – erstattet med **"Klar / platform & kanaler"** |
| "intet nyt at bygge" | Fjernet overalt – erstattet med ærlig "bygges oven på fundament"-narrativ |
| "Trojansk Hest" | Fjernet – erstattet med "Sådan virker det i praksis / Case: Pilot-butik" |
| "FB Admin" node | Omdøbt til **"Board Templates"** (det rigtige systemnavn) |

---

## Proof strip (slide 6 – Board Templates)

Baseret på screenshot af det rigtige amba admin-system (logget ind som Karsten Toksvig):
- 37 aktiverede · Valider alder i Coop App
- 19 aktiverede · Ølsmagning  
- 5 aktiverede · Medlemsmøde 2026
- Dækker: SuperBrugsen · Dagli Brugsen · Kvickly

---

## QuickInfo-statistikker (slide-qi – RIGTIGE tal)

| KPI | Værdi |
|---|---|
| Aktive butikker 2025 | 797 |
| Aktiverede templates | 500K+ |
| Opslag i Coop App | 638K |
| Opslag på Facebook | 1,2M |
| Ordre på Facebook | 16,2M |
| Estimeret omsætning | 1,6–1,8 MIA kr. |

---

## Testimonialer (slide-qi)

- *"Det er nemt og det virker!"* – **Jesper Thomsen**, Kvickly Åbyhøj
- *"QuickCoop fungerer virkelig godt i en travl hverdag"* – **Pia Friis**, SuperBrugsen Steensballe
- *"QuickInfo er hurtig til at svare og hjælpe. Butikkerne er yderst tilfredse"* – **Paul Svith**, Butikspartner, Service desk

**Carsten Toksvig-citat:**
> *"Vi har et virkelig godt samarbejde med QuickInfo. De er altid lydhøre over for vores behov, arbejder effektivt og leverer løsninger, der skaber mærkbare resultater for os. Det gør dem til en værdifuld samarbejdspartner i vores daglige arbejde."*

---

## Tidslinje (slide-8)

- **Marts 2026** – Beslutning (godkendelse + valg af 3 pilotbutikker)
- **April 2026** – Opsætning (quickinfo.dk config, iframe-test, QR-materialer)
- **1. maj 2026** – Pilot Launch (Tæl Skridt + Spin + 1 Mikro-afstemning)
- **1. juli 2026** – Evaluering & Scale (data til amba, beslutning om national udrulning)

---

## Næste skridt / potentielle forbedringer

- [ ] Prisindikation / serviceaftale-model med QuickInfo (hvad koster det rent faktisk?)
- [ ] Tilføj slide om forventet ROI / KPI-mål for piloten
- [ ] Overvej om "6 uger" er realistisk – eller om det bør være "8-10 uger"
- [ ] Evt. tilføj et konkret butiksnavn som bekræftet pilot-kandidat

---

## Server-kommando

```powershell
cd C:\AI\AMBA
python -m http.server 8080
```
Åbn: http://localhost:8080/index.html  
Hard refresh: **Ctrl+Shift+R**
