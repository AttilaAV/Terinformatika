# Térinformatika Beadandó

## Bevezetés
Ez a projekt egy interaktív webtérképet hoz létre a Leaflet nyílt forráskódú JavaScript könyvtár segítségével. A térkép Budapest jelentős nevezetességeit mutatja be, különféle térképi funkciók segítségével, mint például jelölők egyedi ikonokkal, alaptérképek, egy történelmi kép átfedés, GeoJSON vonal és egy kör egy adott nevezetesség körül.

## Térkép jellemzők
### Jelzőpontok
- Három jelzőpont Budapest fontos helyszínein: a Parlament, a Hősök tere és a Citadella.
- Minden jelzőpont saját magyar zászló ikonnal rendelkezik és egy felugró ablakkal információkkal.

### Történelmi kép átfedés
- Egy történelmi térkép átfedése Budapest felett, amely be- és kikapcsolható.

### GeoJSON Vonal
- Egy GeoJSON vonal, amely összeköti a három jelölőpontot.

### Kör
- Egy kör a Parlament körül, hogy kiemelje annak területét.

### Alaptérképek
- Három alaptérkép: OpenStreetMap, egy utcai térkép (CartoDB-ből) és műholdas kép (Google Maps).

## Rétegek és Rétegvezérlés
- Rétegek a jelzőpontok, a történelmi kép, a GeoJSON vonal és a kör számára.
- A rétegvezérlés lehetővé teszi a felhasználók számára, hogy váltogassanak az alaptérképek és a különböző funkciók között.

## Adatok
- A nevezetességek adatai és a történelmi térkép általános forrásokból származnak.

## Licenc
A projekt kódja és dokumentációja MIT licenc alatt áll.
