# Vizualizacija turističkih podataka Hrvatske 2025.

Projekt iz kolegija Vizualizacija podataka: vizualizacija dolazaka i noćenja turista po županijama u 2025. godini.

## Podaci

Podaci su preuzeti s portala Hrvatske turističke zajednice:
https://www.htz.hr/hr/poslovna-inteligencija/informacije-o-tijeku-turisticke-godine

Za svaki mjesec izdvojeni su broj dolazaka domaćih i stranih turista te broj noćenja po županijama.

## Tehnologije

- D3.js
- HTML5 i CSS
- GeoJSON

## Pokretanje

1. Klonirati repozitorij:
```
git clone https://github.com/Lucija611/VizualizacijaPodataka-projekt.git
```

2. Ući u mapu projekta:
```
cd VizualizacijaPodataka-projekt
```

3. Pokrenuti lokalni server:
```
python -m http.server 8000
```

## Grafovi

- **Karta** — odabir vrijednosti (ukupni, strani ili domaći turisti, noćenja), klik na županiju prikazuje linijski dijagram
- **Linijski dijagram** — prikazuje trend kroz godinu za odabrane županije (maksimalno dvije)
- **Stupčasti dijagram** — sliderom se mijenja mjesec i uspoređuju dolasci i noćenja po svim županijama
