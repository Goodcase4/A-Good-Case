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

### Filbeskrivelser

- **index.astro** – forsiden
- **productlist.astro** – viser alle de forskellige produkter
- **productdetails.astro** – viser detaljer om det produkt man har klikket på.
- **about.astro** – fortæller om brandet/firmaet
- **general.css** – styrer designet og har reset
  **custom.css** – indeholder vores variabler

---

## Navngivning

Vi har navngivet vores filer, variabler og funktioner så de så tydeligt som muligt er selvforklarende.

## Data og JSON-struktur

Vi henter data fra et API i JSON-format.

## Git og branches

Vi har brugt GitHub til at samarbejde om projektet.

Vi har arbejdet med branches, så vi ikke sad og ændrede i det samme på samme tid.

Vi navngav branches alt efter hvilke elementer/funktioner der blev lavet.

### Workflow

1. Lave en branch
2. Kode en feature
3. Committe ændringer
4. Pushe til GitHub
5. Merge til main når det virkede

Det gjorde det nemmere at holde styr på, hvem der lavede hvad.

## Bæredygtighed

Vi har tænkt bæredygtighed ind i projektet ved at komprimere alle vores billeder til webp.

## Udfordringer undervejs

- Linke til pages
-

## Mulige forbedringer

Hvis vi skulle arbejde videre med projektet, kunne vi forbedre det ved at tilføje:

- generelt bare færdigkode sitet

## Gruppemedlemmer

- Caroline Amalie Schytte Hemmingsen
- Julie Petersen Bosch
- Katrine Therkildsen Madsen
- Patricia Klindt Brokholm
