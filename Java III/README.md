# Java III – Klinika e CSS: Shpeto afishen

## Pershkrimi

Ne kete detyre kemi krijuar nje afishe per Klubin e Debatit duke perdorur HTML dhe CSS.

Afisha permban:
- Titullin e aktivitetit
- Daten dhe oren
- Vendin
- Pershkrimin
- Linkun per kerkimin e informacionit
- Tri etiketa: Falas, Vende te kufizuara dhe Edhe online

Linku "Kerko informacion" hap Gmail per te derguar nje email.

## CSS

Kemi perdorur CSS te jashtem ne skedaret:
- `style.css`
- `gabime.css`

Ne CSS kemi perdorur:
- Klasa
- Variabla CSS
- Box model
- `box-sizing: border-box`
- `hover`
- `focus-visible`
- Media query per ekranet e vogla

## Gabimet e CSS

Ne `gabime.css` kishte konflikt ndermjet `#poster` dhe `.poster`.

`#poster` kishte specifike me te madhe se `.poster`, prandaj rregulli i ID-se fitonte ne kaskade.

Gjithashtu, `width: 700px` dhe `padding: 80px` mund te shkaktonin overflow ne ekranet e vogla.

Problemi u rregullua pa perdorur `!important`, duke perdorur gjeresi responsive dhe `box-sizing: border-box`.

## Responsive

Afisha pershtatet edhe per ekranin 360px, ne menyre qe paneli te mos dale jashte ekranit.

## Accessibility

Kemi perdorur `:focus-visible` te linku "Kerko informacion", ne menyre qe fokusi te jete i dukshem kur navigojme me tastiere.

## Reflektim

Rregulli `#poster` fitoi ndaj `.poster` ne kaskade sepse selektori me ID ka specifike me te madhe se selektori me klase.

E rregulluam konfliktin pa perdorur `!important`.