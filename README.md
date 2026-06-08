# express.EMPIRIA — Parťák 🔧

Koncept a klikací prototyp mobilnej appky pre **empiria.sk** — slovenský B2B veľkoobchod s vodou, kúrením, plynom, sanitou a tepelnými čerpadlami (rodinná firma, od 1991).

> Appka, ktorá obsadí najdrahší moment montérovho dňa — *„som na stavbe, niečo mi chýba, a chcem to teraz"* — a z veľkoobchodu spraví platformu.

## 🔗 Naživo

| Stránka | Odkaz |
|---|---|
| **Live prototyp** (2 appky, klikací) | https://leumasdam.github.io/empiria-app/ |
| **Artboards** (export do Figmy) | https://leumasdam.github.io/empiria-app/screens.html |
| **Case study** | https://leumasdam.github.io/empiria-app/case.html |
| **Brand & UI kit** | https://leumasdam.github.io/empiria-app/brand.html |

## 🎯 Koncept — flywheel

Empiria je spojka **výrobca → realizačka → investor**. Appka má dve strany jednej mince:

- **Parťák** (montér) — skenuj & nájdi diel, živý sklad 17 predajní, stavby ako projekty, konfigurátor TČ, **zákazky/leady** z Empiria siete, vernostka.
- **Kúpeľne** (investor) — návrh kúpeľne, AR „skús si kúpeľňu", rezervácia v štúdiu, **nájdi overeného montéra**.

Marketplace *„nájdi montážnika ↔ leady"* ich spája do kolobehu:

> Empiria pošle lead montérovi → montér má prácu → nakúpi materiál → vyšší level → prednostné leady ↻

## 🎨 Identita

Postavené na **reálnej brand identite** z firemného archívu, nie na generických assetoch:

- **express.EMPIRIA** navy `#192B37` · **EMPIRIA červená** `#D7282E` · **kúpeľne** šalviová `#AFC0BC`
- Maskot-inštalatér · motív prerušovanej čiary · prerezané „A" v logu
- Reálne fotky predajní, personálu, sortimentu a mapa pobočiek
- Typografia Inter

## 🗂️ Štruktúra

```
index.html     — live prototyp (Parťák + Kúpeľne, prepínač, splash animácia)
screens.html   — board všetkých obrazoviek (Figma-ready artboards)
case.html      — UX/UI case study
brand.html     — brand & UI kit
img/           — reálne brand assety a fotografie
```

## 🛠️ Technológie

Čisté **statické HTML / CSS / JS** — žiadny build, žiadny backend. Splash používa CSS animácie, prechody obrazoviek View Transitions API (s fallbackom).

### Nasadenie na WordPress / iný web
Keďže je to statika, dá sa:
1. **iframe** existujúcej URL do WP *Custom HTML* bloku (najrýchlejšie), alebo
2. nahrať priečinok cez FTP do podpriečinka (napr. `empiria.sk/partak/`).

---

*Koncept · nie je oficiálny produkt Empiria. Brand assety použité ilustratívne.*
