


Reflektion

Flexbox passar bra för mina höjdpunktskört för att layouten blir mer responsiv och följer 
sidan beroende på om den blir större eller mindre, eller omfler objekt/kort läggs till.
Korten kan anpassa sig efter skärmens brädd utan att layoten går sönder.

Exempel:
.kort-rad har jag display: flex; för att 
alla element i den klassen kommer ärva flex egenskaper
display: flex; för att alla element lägger sig 
horisontellt bredvid varandra istället för att vara på höjden
Detta horizontellt->  --- --- ---            Vertikalt  --- 
                                                        ---
                                                        ---
                                                        ---
display: flex; lägger på horizontellt, annars styrs layoten
av webbläsarens standardregler vilket block-elemt alltid har
tex div, p, h1, och section 
(startar alltid på ny rad och tar
upp hela bredden)


README · Trestegsmetoden
Att förstå och förklara sin kod i README.md är en del av passet — och samma typ av fråga kommer på examinationen (Flexbox vs Grid, när vilket). Det duger inte att klistra in en definition från nätet. Peka på din kod.

Peka på hyllan: selektorn där du satte display: flex (t.ex. .kort-rad).
Peka på böckerna: korten som blev flex-items utan manuella procentbredder.
Peka på resultatet: de ligger i en riktning, gap sköter luften, flex-wrap räddar smal skärm. Grid behövs inte här — du har inte rader och kolumner samtidigt.


Feedback: Display flex inline->ta bort inline och lägg i extern CSS fil
Feedback: Flex wrap inline->ta bort och lägg i extern CSS fil 
Feedback: Div class->article class
