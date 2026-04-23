# Teknisk dokumentation – A Good Case - Gruppe 4

## Om casen

Vi fik til opgave at skulle redesigne firmaet "A Good Case"'s website. Først skulle vi lave en prototype af sitet, som vi kom frem til via en gennemgribende designproces.
Dernæst skulle prototypen pitches for kunden 'A Good Case' og til sidst kodes ved brug af astro i vs code ved brug af et api vi selv skabte, i 'Supabase' ud fra kundens eksisterende produkter.

## Links

- GitHub repository: https://github.com/Goodcase4/A-Good-Case
- GitHub Pages:
- Figma: https://www.figma.com/design/jBxyd6CKIbIUcF3btmn25w/A-GOOD-CASE?m=auto&t=l7eFu0h8pqh5zebi-6

## Projektstruktur

Projektet er opdelt i HTML, CSS og JavaScript-filer.

```
pages/
├── index.astro
├── productlist.astro
│   └── productdetails.astro
├── about.astro
├──details
   └── [id].astro

├── css/
│   └── custom.css
│   └── general.css
│
├── components/
│   ├── About_card_1.astro
│   ├── About_card_2.astro
│   ├── Btn_green_brown_grey.astro
│   ├── Btn_tilmeld.astro
│   ├── Card.astro
    ├── Cart_btn.astro
    ├── Carrousel.astro
    ├── Header.astro
    ├── Footer.astro
    ├── Marquee.astro
    ├── Miljo_banner.astro
    ├── Nyhedsbrev.astro
    ├── Pop_up_age.astro
    ├── Smagekase.astro
│   └── Sortering_filter_produktliste.astro
└── README.md
```
