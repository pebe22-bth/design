
Prestanda
=======================

En utvärdering av tre webbplatsers prestanda, genom test av hur snabbt de laddas samt en analys och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.

Urval
-----------------------

Vi använder samma webplaster som i föregående uppgift, vilket är 3 färgstarka artisters webplatser med ganska mycket bilder. Jag har valt ut tre sidor i respektive webplas där jag mäter prestandan:

Jag bestämde mig för:
- https://dregen.se/ - Svensk artist
   - dregen.se
   - dregen.se/records
   - dregen.se/riff-beer
- https://fewocious.com/ - 20-åring som nått en bred publik tack vare NFT
   - fewocious.com
   - fewocious.com/art 
   - fewocious.com/about
- https://www.josbrolmann.com - En random konstnär verksam i Amsterdam.
   - josbrolmann.com
   - josbrolmann.com/about
   - josbrolmann.com/news  
  

Metod
-----------------------

Prestandamätningen har gjorts med hjälp av [Google Pagespeed](https://pagespeed.web.dev/), vilket är en tjänst som automatisk testar och summerar prestanda och användbarhet utifrån fyra perspektiv:
- Performance
- Accessability
- Best practices
- SEO
Testerna görs och sammanfattas för Desktop- och Mobile-klient och betygssätts i skalan 0-100, där 100 är bäst. Enligt Googles måttstock är 0-49 dåligt (rött), 50-90 varning (gul) och 91+ bra (grönt).

Webplasternas prestanda och innehåll analyseras även med hjälp av Developer tools i Chrome webläsare, där följande mäts och sammanfattas:
- Speed
- no of resources
- size in MB
Dessa mätningar görs i tre omgångar på respektive websida för att få jämnare, mer användbart medelvärde.
I resultatet nedan har jag bedömt att laddningstider under 2 sekunder är bra (grön). LÄngre laddningstider markeras med gult.

Resultaten sammanfattade i excel och redovisas nedan.

Resultat
-----------------------


### Webplats 1: Dregen [dregen.se](https://www.dregen.se)


![Websidan](%assets_url%/img/kmom04/websites/dregen-webpage.jpg)  {.small}


<iframe title="Dregen performance statistics" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQqlYfqAmrERg6fzOiY-yjKtzZqaTz2SpQG07vhqarXs1swm2WTEm7yJQ4v9tf1RRfIleUZO_L5lW2g/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

Kommentarer till resultat: 
- Prestanda och användberhet är sammantaget bra, med vissa undantag
- Prestanda är sämre på mobila devices än desktop, vilket borde kunna gå att förbättra genom mer responsiv anpassning.
- Användberhet är aningen sämre på mobile devices än desktop.
- Laddningstider ligger mellan 1,5 och 3 sekunder.



### Webplats 2: Fewocious.com [fewocious.com](https://fewocious.com/)


![Websidan](%assets_url%/img/kmom04/websites/fewocious-www.png)  {.small}


<iframe title="Fewocious.com performance statistics" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQqlYfqAmrERg6fzOiY-yjKtzZqaTz2SpQG07vhqarXs1swm2WTEm7yJQ4v9tf1RRfIleUZO_L5lW2g/pubhtml?gid=70715650&amp;single=true&amp;widget=true&amp;headers=false"></iframe>


Kommentarer till resultat: 
- Prestanda och användbarhet är sammantaget bra, med vissa undantag
- Prestanda är sämre på mobila devices än desktop, vilket borde kunna gå att förbättra genom mer responsiv anpassning.
- Accessability, SEO och best practice är lika mellan desktop och mobile klient.
- Best practice uppfylls till 100%, vilket är högsta betyg.
- Laddningstider ligger mellan 1,4 och 2,5 sekunder.


### Webplats 3: [Jos Brolmann](https://www.josbrolmann.com/)

![Websidan](%assets_url%/img/kmom04/websites/jos-www.png)  {.small}

<iframe title="Jos Brolman performance statistics" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQqlYfqAmrERg6fzOiY-yjKtzZqaTz2SpQG07vhqarXs1swm2WTEm7yJQ4v9tf1RRfIleUZO_L5lW2g/pubhtml?gid=769309446&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

Kommentarer till mätningar: 
- Prestanda och användbarhet är sammantaget bra, med vissa undantag
- På 2 sidor är prestanda sämre på mobila devices än desktop, men på en sida har mobile bättre prestanda.
Prestandan borde gå att förbättra genom mer responsiv anpassning.
- Accessability, SEO och best practice är i stort sett lika mellan desktop och mobile klient.
- Laddningstider ligger mellan 1,4 och 4,8 sekunder, där speciellt den tredje websidan josbrolmann.com/news borde gå att förbättre genom optimering.
  

Analys
-----------------------

Alla tre webplaster har väldig lite funktioner för responsivitet med få skillnader i mobil respektive desktop-klient. De fungerar alla bra och får bra betyg i SEO, Accessability och Best practice, men borde generellt gå att förbättra för mobila klienter.
Några sidor är tunga med mycket bilder och total storlek i MB, vilket är förståeligt då webplasterna är skyltfönster för artister - men risk för att laddningstider ökar avsevärt med lägre bandbredd. Detta är dock inget som ingick i testet.

Webplats 3, [Jos Brolmann](https://www.josbrolmann.com/) utses till testets vinnare, då det lyser mest grönt i resultatet för den webplasten. Obs att testet mäter prestanda och tekniska kvaliteter och inte kulturella värden! (då hade Dregen vunnit.)

Referenser
-----------------------

[Google pagespeed](https://developers.google.com/speed/docs/insights/v5/about)


Övrigt
-----------------------

Uppgiften löstes individuellt.