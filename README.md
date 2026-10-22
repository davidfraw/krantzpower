# Krantzpower

Osobní deník spánku, nálady, jídla a tréninků. Jedna HTML stránka, funguje offline a dá se nainstalovat na plochu telefonu.

- **Dnes:** spánek, nálada a energie ráno i večer, jídla a bílkoviny, váha a pas.
- **Trénink:** série podle cviků, hodnoty z minula, pauza mezi sériemi, rekordy.
- **Týden:** průměry a den po dni.
- **Pokrok:** grafy síly a váhy.

Data jsou uložená jen v prohlížeči telefonu (localStorage). Nic se nikam neposílá. Zálohu stáhneš v sekci Pokrok → Záloha jako soubor JSON; tamtéž se dá záloha nahrát zpátky.

## Soubory

- `index.html` – celá appka
- `sw.js` – offline cache
- `manifest.json`, `icon.svg` – instalace na plochu

## Nasazení

GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `(root)`.
