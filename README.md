# ⚡ Prekladač ľudského chápania

Satirický „pohotovostný dešifrovací terminál“, ktorý preloží zachytenú frázu do zrozumiteľnej slovenčiny — s láskavým humorom a reálnym psychologickým jadrom (Gottman, Tannen, Chapman, Lerner, Johnson, Levant, Watzlawick).

## Funkcie
- 🧠 AI · Vyššie chápanie — odpoveď generuje Gemini AI (so šifrovaným napojením kľúča)
- 📖 Výskumná databáza — 16 poznatkov z reálnych štúdií (Gottman, Tannen, Mehl/Science, Hyde, Levant…), z ktorých čerpajú odpovede
- ♀ / ♂ voľba, kto frázu vyslovil — až potom sa zobrazí vstupné pole
- ⚡ Dešifrovanie vloženej frázy (vstavaná databáza pre oba režimy)
- 🚨 DEFCON škála úrovne ohrozenia (5 = pokoj, 1 = kritický stav)
- 🛟 Odporúčaná stratégia prežitia
- 📚 Rozkladací zoznam odborných zdrojov ku každej odpovedi
- 🎲 Náhodná fráza na vyskúšanie (podľa zvoleného režimu)
- 🗂 Archív dešifrovaní so symbolom pohlavia (ukladá sa lokálne v prehliadači)

## Spustenie
Celá aplikácia je jeden súbor — `index.html`. Stačí ho otvoriť v prehliadači.

### GitHub Pages
1. Nahrajte obsah tohto priečinka do repozitára
2. Settings → Pages → Deploy from branch → `main` / root
3. Aplikácia beží na `https://<user>.github.io/pochopnas/`

## Poznámka
Tlačidlo ⚡ DEŠIFROVAŤ používa vstavanú databázu fráz (funguje offline). Tlačidlo 🧠 AI volá Gemini API; pri zlyhaní automaticky odpovie vstavaná databáza.

### Bezpečnosť API kľúča
Kľúč nie je v kóde uložený ako text — je XOR-šifrovaný a rozdelený na fragmenty, skladá sa až za behu. Pre plnú ochranu odporúčame v Google AI Studio nastaviť „Website restrictions“ na doménu vašich GitHub Pages.

Satirický projekt s láskou. Skutočne overená dešifrovacia metóda: opýtať sa a počúvať. ♥
