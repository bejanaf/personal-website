Grid 16.04.2021

<section> / <main>

Grid-Muster

</section> </main>

dispay: grid;
gap: 20px; wie viel Platz zwischen meinen grid -elementen
grif-template-columns: 30rem 20 rem 10 rem; 3 Spalten
mit bsp 10 divs, 10 spans

grif-template-columns: repeat(5; 10rem); 5spalten
grif-template-columns: repeat(5; 1fr); 5spalten

50 px (5, 5rem 2rem); erste spalte immer 50 px

grif-template-columns: 100px auto 100px;

fr = fraction unit, neue funktion
grif-template-columns: 1fr 2fr; zweite spalte doppelt so große woe die erste
auch hier justify-content anwendbar, vieles ähnlich zu flex

grid-auto-rows: 50px;
align-content vertikale ebene, y-achse

repeat (4, 1fr)
conteriner item one
grid-column: 1 / 4; 1 spalte bis zur vierten lang (bevor die vierte losgeht)

grid-row: span 2; 2spalten lang

grid-auto-flow: dense; (grid versucht lücken mit passenden elementen zu füllen)
