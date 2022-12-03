---
Title: Load
Description: Load analysis
Template: analysis
---

Laddningstid
=======================

Uppgiften handlar om att undersöka och utvärdera olika webbplatsers laddningstid och om de kan förbättras för användbarhet. 

Urval
-----------------------

De webbplatser jag har valt att undersöka är [1177](https://www.1177.se), [Göteborgs Stad](https://www.goteborg.se) och [Västtrafik](https://www.vasttrafik.se). Jag valde att undersöka dessa sidor på grund av att de alla har en stor relevans för invånare i Göteborgs stad. Användbarheten och laddningstiden har således en stor inverkan på hur användare upplever dessa resurser. 

Metod
-----------------------
Undersökningen utfördes genom att använda utvecklarverktyget i Chrome och PageSpeed Insights för att mäta webbplatsernas värden. 

Resultat
-----------------------
### 1177
![1177 Hemsida](%base_url%/image/1177.png?q=50)
### Göteborgs Stad
![Göteborgs stad Hemsida](%base_url%/image/goteborg.png?q=50)
### Västtrafik
![Västtrafiks hemsida](%base_url%/image/vasttrafik.png?q=50)
<div class="iframe-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQBvIWuzmocyjRIY_7A2VTe5vQb7MckDEI4KMKvjOssOvlo4dC-Jcc97pD59epQDpBbz-QpjwIFmvgA/pubhtml?widget=true&amp;headers=false"></iframe>
</div>


Analys
-----------------------
Av PageSpeed Insights fick endast Göteborgs Stads mobila version godkänt och Västtrafiks skrivbords version godkänt. Resterande passerade ej testet. Det som i alla fallen gjorde att webbplatsen ej klarade testet var Cumulative Layout Shift, vilket innebär att layouten kan skiftas vilket påverkar användarens upplevelse. För att förbättra webbplatserna behöver då detta åtgärdas vilket som kan göras genom att sätta width och height på bilder, vilket även PageSpeed Insights gav som förslag på utveckling för webbplatserna. Att reducera JavaScript och CSS som inte används var också förslag för förbättrad prestanda. 

### Rangordning
Baserat på mätvärden rangordnar jag webbplatserna
1. Göteborgs Stad 
2. Västtrafik
3. 1177

Göteborgs Stads Hemsida hade den näst snabbaste laddningstiden samt även den minsta totala storleken. Den klarade även PageSpeed Insights test för den mobila versionen och trots att den inte fick godkänt på CLS var värdet 0,12 jämfört med de andra webbplatserna som hade 0,4.

Västtrafik rangordnar jag som tvåa trots laddningstid på 2s och total storlek på 2,9MB. Västtrafik klarade PageSpeed Insights för Skrivbordsversionen. 

1177 hade snabbast laddningstid men klarade inte PageSpeed Insights testen för varken mobil eller skrivbordsversion och därför rankar jag den webbplatsen sist.

### Laddningstid
En laddningstid som jag själv uppfattar som snabb är under eller lika med 1s. En långsam laddningstid å andra sidan skulle jag säga är över 2s. Mitt urval av webbplatser är klarar då inte mitt gränsvärde för att klassificeras som snabba. I allmänhet upplever jag webbplatserna som relativt snabba och responsiva. Att ladda in bilder tar i vissa fall lite längre tid. 

Övrigt
-----------------------
Isabella Garneij