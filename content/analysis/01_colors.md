




Färganalys
=======================

En utvärdering av tre webbplatsers färgval och känslan de signalerar.

Urval
-----------------------

Jag ville använda färgstarka och vad jag uppfattar som moderna webplatser så tänkte att det borde finnas artister och personer som gärna vill sticka ut och upplevas som nåt extra med hjälp av sina webplatser, typ artister, konstnärer eller extrema politiker.

Jag bestämde mig för:
- https://dregen.se/ - Svensk artist
- https://fewocious.com/ - 20-åring som nått en bred publik tack vare NFT
- https://www.josbrolmann.com - En random konstnär verksam i Amsterdam. 
  

Metod
-----------------------

Jag använder [Adobe color](https://color.adobe.com/) för analys av färgerna, den innehåller en "color picker" som jag enkelt kan fånga färgerna på webplatsen och även plotta ut dem i ett färghjul för att avgöra vilket typ av färgschema det är (om det är något, eller bara random färger).
Jag tittar i HTML-koden och CSS för att fånga vilka fonter som används och här är Developer mode i Chrome ett bra verktyg. Där kan jag även hitta exakt färgkoder då det visade sig att color pickern var mindre exakt om färgerna nyttjar gradient eller liknande effekter. Fonterna hittade jag lättast genom att titta på "sources" i utveckliongsverktyget, där framgår om fonten laddas från t.ex google fonts eller om de ligger som del i webplatsen. Ligger de lokalt kan jag se en preview på fonten i developer mode så jag vet att det är rätt.



Resultat
-----------------------


### Webplats 1: Dregen [dregen.se](https://www.dregen.se)


![Websidan](%assets_url%/img/kmom04/websites/dregen-webpage.jpg)  {.small}
  
Färgpaletten på webplasten består framförallt av färgerna nedan och schemat liknar mest typen "split complementary".  

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
    <td style="height: 50px; width: 50px; background-color: #222">
    <td style="height: 50px; width: 50px; background-color: #FFF">
    <td style="height: 50px; width: 50px; background-color: #df1910">
    <td style="height: 50px; width: 50px; background-color: #0096bc">
    <td style="height: 50px; width: 50px; background-color: #ffc000">
</tr>
<tr>
    <td>#222222</td>
    <td>#FFFFFF</td>
    <td>#DF1910</td>
    <td>#0096BC</td>
    <td>#ffc000</td>
</tr>
</table>
 ![Colorscheme](%assets_url%/img/kmom04/websites/dregen-colorscheme.png) {.smallest}
  
Typsnitten som används är
  
- h1-h3         font-family: "Dregen Fat", Impact, "Arial Black", "Arial Bold", Arial, sans-serif;
- body text:    font-family: Helvetica, Arial, sans-serif;
  
"Dregen Fat" är vad jag kan förstå en egen utvecklad font.
  
### Webplats 2: Fewocious.com [fewocious.com](https://fewocious.com/)


![Websidan](%assets_url%/img/kmom04/websites/fewocious-www.png)  {.small}

Färgpaletten på webplasten består framförallt av färgerna nedan. Färgschemat liknar inte direkt någon av de standardiserade typerna.  

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
    <td style="height: 50px; width: 50px; background-color: #fefefe">
    <td style="height: 50px; width: 50px; background-color: #df1910">
    <td style="height: 50px; width: 50px; background-color: #efbb31">
    <td style="height: 50px; width: 50px; background-color: #5ed933">
</tr>
<tr>
    <td>#fefefe</td>
    <td>#df1910</td>
    <td>#efbb31</td>
    <td>#5ed933</td>
</tr>
</table>
 ![Colorscheme](%assets_url%/img/kmom04/websites/fewocious-colorscheme.png) {.smallest}

Webplatsen har även en funktion att ändra tema från blå moln-bakgrund med vita moln till en rosa bakgrund med blå molnsom sticker ut lite mer. Den ändirngen påverkar dock inte övriga färger.
Typsnitten som används är

- h2:         font-family: FewoFont-Regular, Shadows Into Light, Open Sans, Helvetica Neue, helvetica, roboto, arial, sans-serif;
- body text:    font-family: Nunito Sans, Helvetica Neue, helvetica, roboto, arial, sans-serif;
  
Websidan innehåller inte längre mängder med text, därav få rubriknivåer. 
"FewoFont-Regular" ser ut att vara en egenutvecklad font som ligger lokalt på webplatsen. 
"Nunito Sans" är en Google font.
Generellt är webplatsen byggd med fokus på att vara orginell och det är inte 100% uppenbart vad som är klickbart och inte. 
Det längre textstycke som finns använder en normal font och är bra läsbar, dock upplevs den som tråkig med tanke på hur resten av webplasten ser ut.  

### Webplats 3: [Jos Brolmann](https://www.josbrolmann.com/)

![Websidan](%assets_url%/img/kmom04/websites/jos-www.png)  {.small}

Färgpaletten på webplasten består framförallt av färgerna nedan och schemat liknar det åtminstone Adobe kallar för "square" typen "split complementary".  

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
    <td style="height: 50px; width: 50px; background-color: #3860a8">
    <td style="height: 50px; width: 50px; background-color: #63d138">
    <td style="height: 50px; width: 50px; background-color: #d54ba3">
    <td style="height: 50px; width: 50px; background-color: #f79e00">
    <td style="height: 50px; width: 50px; background-color: #00c6f7">
</tr>
<tr>
    <td>#3860a8</td>
    <td>#63d138</td>
    <td>#d54ba3</td>
    <td>#f79e00</td>
    <td>#00c6f7</td>
</tr>
</table>
 ![Colorscheme](%assets_url%/img/kmom04/websites/jos-colorscheme.png) {.smallest}


Typsnitten som används är

- h2:         font-family: Arial, Helvetica Neue, Helvetica, sans-serif;
- body text:    font-family: Nunito Sans, Helvetica Neue, helvetica, roboto, arial, sans-serif;
  
Websidan innehåller inte längre mängder med text, därav få rubriknivåer. 
"Nunito Sans" är en Google font.

Det här ytterligare en webplats om en konstnär och har en ambition att vara konstnärlig och professionell. Den är mer strikt jämfört med den ovan. 

Analys
-----------------------

Jag har valt att analysera webplaster som har ambition att förmedla uttryck som återspeglar artisten de handlar om, samt marknadsföra dessa. Alla 3 webplasterna har eller länkar till möjloghet att köpa deras verk.
Dregen tycker jag lyckats bäst i att återspegla hans image i webplatsenes tema - med en font som sticker ut och mycket detaljer i bakgrund som förstärker intryck och färger som passar väl med bilder och den svart-vita dregen punk-style.

Alla tre webplatserna upplever jag som väldesignade och att de hjälper till att förmedla (det jag uppfattar) är den image respektive kosntnär/artist vill förmedla. På "Fewicious" webplats är det tydligt att utseende och konstnärliga detaljer går före användbarhet, men inget som är stoppande.

Inga direkta problem med webplatsen och tydlig text, förutom möjligen att den vita texten på "jos" webplats med en inte alltför mörk bakgrund inte blir så lättläst. 
Det finns ingen möjlighet att byta till ett mörkt tema på någon av webplasterna, förutom att en av dem ger möjklighet till rosa himmel istället för blå ;)

Referenser
-----------------------

Inga referenser används.  


Övrigt
-----------------------

Uppgiften löstes individuellt.