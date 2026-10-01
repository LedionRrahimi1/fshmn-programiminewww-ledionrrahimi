# Java II — Muzeu i sendeve

Faqe e thjeshtë HTML për një ekspozitë digjitale me tri sende: Çelësi, Filxhani dhe Bileta. Përdor SVG-të e dhëna, lidhje brenda faqes dhe `<details>` për historinë e fshehur.

## Skedarët

| Skedari | Roli |
|---|---|
| `index.html` | Struktura e faqes |
| `style.css` | Stili i lejuar (minimal) |
| `celesi.svg`, `filxhani.svg`, `bileta.svg` | Të dhënat hyrëse (ikonat) |
| `README.md` | Ky sqarim |

## Para kodimit

- **Hyrjet:** skedarët SVG, tekstet e ekspozitës, klikimet te lidhjet `#celesi` / `#filxhani` / `#bileta` dhe te `summary`.
- **Daljet:** faqja e renderuar me tri seksione, ikona dhe histori të palosshme; kërkesat HTTP `200` për HTML, CSS dhe SVG.
- **Rast normal:** hapet `index.html`, shihen tri sende, klikohet «Historia e fshehur» dhe shfaqet paragrafi.
- **Rast kufitar 1:** klik te lidhja e navigimit (p.sh. `#bileta`) — faqja kalon te seksioni i duhur pa faqe të re.
- **Rast kufitar 2:** kërkesë për skedar që s’ekziston (p.sh. `/Java%20II/mungon.html`) — serveri kthen `404`.

## Si ta hapësh

```sh
python -m http.server 8080
```

Pastaj hap: `http://localhost:8080/Java%20II/index.html`
