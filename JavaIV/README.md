# Java IV – Festivali që përshtatet në çdo ekran

## Çfarë realizova

Krijova një faqe statike për programin e një festivali shkencor. Ajo ka gjashtë karta aktivitetesh, një menu me Flexbox dhe kartat të vendosura me CSS Grid. Çdo kartë ka titull, kategori, orar dhe një lidhje që çon te detajet më poshtë në faqe. Imazhi lokal përshtatet me gjerësinë e ekranit. Teksti nuk ka lartësi fikse dhe titulli i fundit ka 104 karaktere për të provuar mbështjelljen në disa rreshta.

## Si hapet

Hap `JavaIV/index.html` në shfletues. Nuk kërkohen instalime ose server, sepse faqja përdor vetëm HTML, CSS dhe imazhin lokal `atomi.jpg`.

## Testet

Testet u bënë në Microsoft Edge duke vendosur gjerësinë e faqes në 360, 768 dhe 1280 px.

| Hyrja | Rezultati i pritur | Rezultati i marrë |
| --- | --- | --- |
| Gjerësi 360 px | 1 kolonë, pa scroll horizontal | 1 kolonë, pa scroll horizontal |
| Gjerësi 768 px | 2 kolona, pa scroll horizontal | 2 kolona, pa scroll horizontal |
| Gjerësi 1280 px | 3 kolona, pa scroll horizontal | 3 kolona, pa scroll horizontal |
| Titulli 104 karakterësh në secilën gjerësi | Qëndron brenda kartës | Qëndroi brenda kartës në të tria gjerësitë |
| Tasti Tab nga fillimi i faqes | Fokusi kalon te lidhjet e menusë | Fokusi kaloi te “Kalo te përmbajtja”, “Aktivitetet” dhe “Informata”, në këtë rend |

## Reflektim individual

Do të zgjidhja Flexbox për elemente në një drejtim, si lidhjet e menusë që mund të kalojnë në rresht tjetër. Do të zgjidhja Grid për kartat, sepse duhen organizuar në rreshta dhe kolona dhe numri i kolonave ndryshon sipas gjerësisë së ekranit.

## AI dhe burimet

Për përfundimin e kodit, kontrollin responsive dhe shkrimin e këtij README u përdor ndihma e OpenAI Codex. Përmbajtja e festivalit është shembull i sajuar. `atomi.jpg` ishte tashmë aset lokal në projekt; burimi i tij origjinal nuk ishte shënuar. Nuk u përdorën burime të jashtme të tjera.
