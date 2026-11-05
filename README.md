# La meva pàgina de SMX

Pàgina web feta per a una pràctica de 2n de **Sistemes Microinformàtics i Xarxes (SMX)**. Mostra els mòduls del curs i l'horari de classe, amb una estètica de finestra retro inspirada en Windows 95 i Internet Explorer 3.0.

## Què hi ha

- `index.html`: estructura de la pàgina, amb seccions d'inici, mòduls i horari.
- `style.css`: estils de la finestra retro i disseny adaptable per a mòbil.
- `nuvols.svg` i `internet-explorer-3-0-1996.gif`: recursos gràfics.

## Detalls tècnics

- HTML i CSS purs, sense frameworks ni JavaScript.
- Pàgina en català (`lang="ca"`).
- L'horari és una taula que es pot desplaçar horitzontalment en pantalles petites, amb `role="region"` i `aria-label` perquè sigui accessible amb teclat i lectors de pantalla.
- Totes les imatges tenen text alternatiu.

## Com veure-la

Clona el repositori i obre `index.html` amb qualsevol navegador:

```bash
git clone https://github.com/aminewe898/La-meva-pagina-de-SMX.git
```

## Llicència

MIT. Consulta [LICENSE](LICENSE).
