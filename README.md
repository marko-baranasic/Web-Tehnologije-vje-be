# Osobni portfolio – Ante Kovač

Statička web stranica izrađena kao Projekt 1 za kolegij **Uvod u web tehnologije**
na Sveučilištu u Zadru, studij SIT, ak. god. 2025./2026.

## Stranice

| Datoteka | Sadržaj |
|---|---|
| `index.html` | Naslovnica – hero sekcija, kratki uvod, 3 kartice |
| `o-meni.html` | Biografija, tablica vještina, popis obrazovanja |
| `projekti.html` | Grid kartica s 4 projekta |
| `kontakt.html` | Kontakt forma + info sidebar |

## Tehnologije

- **HTML5** – semantički elementi: `header`, `nav`, `main`, `footer`, `article`, `section`, `aside`
- **CSS3** – Flexbox, Grid, CSS varijable (tokeni), media queries
- Bez JavaScripta
- Bez vanjskih frameworka ili biblioteka

## Posebnosti

- **Hamburger izbornik bez JavaScripta** – trik s `<input type="checkbox">` i CSS `:checked` selektorom
- **Pristupačnost** – skip link, vidljiv fokus na svim elementima, alt tekst na slikama
- **Responsive dizajn** – radi na 375px (mobitel) i 1280px+ (desktop)
- **SEO** – unikatan `<title>` i `meta description` na svakoj stranici, Open Graph tagovi

## Kako pokrenuti

1. Klonirati repozitorij ili preuzeti ZIP
2. Otvoriti `index.html` u pregledniku

Ili koristiti **Live Server** ekstenziju u VS Codeu (desni klik na `index.html` → *Open with Live Server*).

## Struktura projekta

```
/
├── index.html
├── o-meni.html
├── projekti.html
├── kontakt.html
├── css/
│   └── style.css
├── img/
│   ├── profil.jpg          ← fotografija (300×300 px)
│   ├── og-preview.jpg      ← Open Graph slika (1200×630 px)
│   ├── projekt-maticna.pjpgng
│   ├── projekt-nautic.png
│   ├── projekt-portfolio.png
│   ├── projekt-raspored.jpg
└── README.md
```

## Live verzija

[https://web-tehnologije-projekt1.netlify.app/](https://web-tehnologije-projekt1.netlify.app/)

## Autor

*Marko Baranašić** – UNIZD SIT, 2026.
