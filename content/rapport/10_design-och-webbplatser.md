---
---
Design och webbplatser
=========================

Introduktion
-----------------------

I dagens teknikfokuserade samhälle är det väldigt vanligt att besökare av webbplatser använder sig av mobila enheter för att besöka webbplatser. Men hur väl är våra webbplatser anpassade för den mobila enheten och hur har webbplatser hanterat innehåll som behöver levereras på en väldigt liten skärm jämfört med en stor monitor?
Denna rapport kommer utvärdera och analysera tre olika länders turistwebbplatsers design ur ett mobilt perspektiv, vad är det för likheter,  olikheter och svagheter mellan den mobila versionen och deras webbversion (dvs den version som är anpassad till att en besökare sitter vid en monitor som oftast är 13 tum eller större).

Urval
-----------------------

Jag valde att först utgå ifrån att se över Sveriges turistwebbplats vilken heter [Visit Sweden](https://visitsweden.com/). För att få lite andra men ändå jämförbara perspektiv så valde jag att även utvärdera Norges och Storbrittaniens tursitwebbplatser. Norges turistwebbplats heter [Visit Norway](https://www.visitnorway.se/) och Storbrittaniens turistwebbplats heter [Visit Britain](https://www.visitbritain.com/).

En av anledningarna att jag valde just turistwebbplatser att utvärdera är för att jag tänkte att turister i ett annat land nog generellt använder en mobil enhet att titta på webbplatser när de befinner sig i det land de besöker. Vilket jag då även tänker att turistwebbplatser borde vara webbplatser som fokuserat lite extra på att skapa en bra mobil upplevelse.

Metod
-----------------------

För att få en bra uppfattning av det mobila perspektivet på ovan webbplatser så använde jag följande metoder.

Först gjorde jag en översiktlig analys av varje webbplats webbversion. Därefter använde jag det inbyggda verktyget developer tools i Google Chrome för att ändra storleken på "min skärm" så att den motsvarade en iPhone6/7/8. På det sättet fick jag se webbplatsens responsiva mobilversion och kunde då jämföra den med deras webbversion.

Jag tog även en skärmdump på både deras webbversion och deras mobila version som referens och inkluderade dem i denna rapport. För att ta skärmdumpen använde jag verktyget [Full page screen capture](https://mrcoles.com/full-page-screen-capture-chrome-extension/) till Chromes webbläsare. Detta tillägg gjorde det möjligt att på ett enkelt sätt ta en bild på deras webbplats i ett steg trots att man behöver skrolla ner över flera skärmlängder för att se hela webbplatsen.

Jag avslutade respektive analys med att göra en Speedtest av både webbplatsens webbversion och deras mobila version med hjälp av Googles mätverktyg [Pagespeed](https://developers.google.com/speed/pagespeed/insights/). Jag noterade där om de hade någon speciell svaghet eller utvecklingsmöjlighet.

Jag avslutar rapporten med att göra en generell analys och jämförelse mellan de tre olika webbplatserna för att se ifall det finns några likheter eller olikheter i hur de har hanterat deras mobila version av deras webbplats.

Resultat
-----------------------

### Visit Sweden
[FIGURE src="image/vSwedenS.png?h=1000" class="right" caption="Visit Sweden mobil"]
[FIGURE src="image/vSweden.png?h=1000" class="right" caption="Visit Sweden webb"]

#### Webbversion
Webbplatsen visit Sweden har en relativt klassiskt layout. De har en horisontell meny längst upp på sidan. En vit bakgrund med inramade bilder och text som länkar till mer information. Bilder, knappar och text som är länkar har någon form av rörelse eller färgskiftning när man för muspekaren över dem för att indikera att de är länkar. Man kan skrolla ner på webbplatsen för att se många olika sektioner med mer information. I botten av sidan finns en sidfot som innehåller en övergripande lista på länkar till mer "matnyttiga" undersidor och kontaktinformation.

#### Mobila skillnader
När man besöker Visit Sweden på en mobil så förändras innehållet att passa den mindre skärmen. Den horisontella menyn försvinner och ersätts med en "hamburgermeny", dvs tre horisontella sträck som man kan trycka på och öppna upp en meny. Mobilmenyn är en kombination av den horisontella menyn och menyn i sidfoten.

Den mobila sidan innehåller exakt samma bilder som webbversionen. Dock för att skapa ett intressantare flöde får vissa bilder ta upp hela skärmen i webbversionen, medans i mobilversionen är alla bilder lika stora, dvs de tar upp hela bredden på mobilskärmen.
I den mobila versionen är det inget som händer när man för muspekaren över länkar, dock är det istället någon form av rörelse eller färskiftning när man trycker på en länk.

#### Speedtest
Visit Sweden får 96 av 100 på PageSpeed för deras webbversion. Det finns därmed väldigt få förbättringsmöjligheter.

Gällande deras mobilversion får visit Sweden 46 av 100 poäng. De får sämre poäng på mobilversionen bl.a. för att "Time to Interactive är hela
10 sekunder, dvs det tar 10 sekunder innan sidan är så pass nerladdad att en besökare fullt ut kan använda alla funktionaliteter på sida.
Ett avsevärt förbättringsförslag är att de skall "Eliminate render-blocking resources" och kan då spara 2.16 sekunders laddningstid, dvs säkerställa att webbplatsen inte har CSS eller Javascript filer som blockerar annat innehåll att skrivas ut.

<div class="clearboth"></div>

### Visit Norway
[FIGURE src="image/vNorwayS.png?h=1000" class="right" caption="Visit Norway mobil"]
[FIGURE src="image/vNorway.png?h=1000" class="right" caption="Visit Norway webb"]

#### Webbversion
Visit Norway har en video som börjar spelas upp automatiskt som det första man möter på deras webbplats. Webbplatsen har inte den klassiska veritkala menyn i toppen på webbplatsen utan endast hamburgermenyn även om man besöker webbversionen med en stor skärm. Trycker man på menyknappen så får man upp en meny som täcker hela sidan och innehåller länkar till deras undersidor.

Skrollar man ner på sidan så består resten av webbplatsen mycket av bilder indelade i horisontella sektioner där man blandar mindre bilder med bilder som tar upp hela sidbredden. Längst ner på sidan har de en sidfot som innehåller länkar till undersidor och kontaktinformation.

#### Mobila skillnader
Den mobila förstasidan ser precis ut som webbversionen med skillnaden att videon inte spelas upp automatiskt utan man behöver trycka på den för att starta videon. Den mobila hamburgermenyn är nerbantad till att endast innehålla en del av de länkar som inkluderades i webbversionen.

Layouten på den mobia versionen är något förändrad. Istället för att endast stapla de bilder som fanns på webbversionen i en lång lista så har man slagit ihop vissa bilder enligt kategorier. Inom varje kategori kan man skrolla även sidled för att få ta del av mer information.
Mobilversionen har ingen speciell indikation när man för muspekaren över en länk utan som Visit Sweden så har man istället en visuell återkoppling först när man trycker på en länk.

#### Speedtest
Visit Norway får 32 av 100 poäng på PageSpeed för deras webbversion. Baserat på den låga poängen är det även en lång lista på förslag till förbättringsåtgärder. Bl.a. "Eliminate render-blocking resources" och att undvika "excessive DOM size", dvs att undvika att ha för många HTML DOM element.

Gällande deras mobilversion får den 6 av 100 poäng. "Time to Interactive" är här 26.7 sekunder och "First Contentful Paint"
5.7 sekunder, dvs tiden innan första texten eller bilden visas. Det primärt förslaget på förbättring är att de skall "Eliminate render-blocking resources".

<div class="clearboth"></div>

### Visit Britain
[FIGURE src="image/vGBS.png?h=1000" class="right" caption="Visit Britain mobil"]
[FIGURE src="image/vGB.png?h=1000" class="right" caption="Visit Britain webb"]

#### Webbversion
Visit Britains webbplats har den klassiska horisontella menyn högst upp på sidan. Skrollar man ner på sidan så innehåller den horisontella sektioner på vit bakgrund och innehåll är primärt bilder men en del text. Det mest på förstasidan är länk till mer information.

Länkarna i sig har oftast (men inte alltid) någon form av visuell återkoppling till besökaren när man för muspekarn över länken. Visit Britain har fler sektioner som ser visuellt olika ut jämfört med Visit Sweden och Visit Norway. Layouten är dock likt placerad enligt ett tydligt balanserat grid. Längst ner på sidan har de en sidfot med länkar till praktiskt information och kontaktuppgifter.

#### Mobila skillnader
Den mobila versionen döljer den horisontella menyn och visar endast hamburgermenyn. Hamburgermenyn är en komprimerad version av den som visades på webbversionen, dock går det att klicka sig fram i menyn till undermenyer som inkluderar all information.

Likt Visit Sweden så har Visit Britain inkluderat samma information direkt i mobilversionen som finns i webbversionen. Informationen är dock något minimerad och sektioner som hade bilder i horisontell ordning i webbversionen har bilderna nu primärt i vertikal ordning. Även sidfoten innehåller samma information i webbversionen och den mobila versionen.

#### Speedtest
Visit Britain får 56 av 100 poäng på PageSpeed för deras webbversion. "Time to Interactive" är här 4.9 sekunder och deras största förbättringsmöjlighet är att "Defer offscreen images", dvs vänta med att ladda bilder som inte syns på sidan från första början.

Webbplatsen får 21 av 100 poäng för deras mobilversion. "Time to Interactive" är här 18.6 sekunder och några av deras förbättringsmöjligheter är att "Remove unused CSS", dvs att inte inkludera CSS regler som inte används och "Avoid multiple page redirects", dvs att undvika att styra om besökaren till andra sidor automatiskt.

<div class="clearboth"></div>

Analys
-----------------------
Det är intressant att se hur lika alla tre ovan webbplatser är i sin utforming av både sin webbversion och framför allt omkonverteringen till deras mobila version. De verkar även till viss del ha samma svagheter om man tar hänsyn till PageSpeed.

Baserat på ovan undersökningar så är det standard att man använder en hamburgermeny som standard för menyer i en mobil version av en webbplats. Visit Norway hade till och med hamburgermenyn på deras webbversion också, vilket ibland kan refereras till att man har designat en webbplats med den mobila enheten i åtanke först och främst.

Den andra aspekten av den mobila layouten som också är tydlig är att innehållet som visas på skärmen oftast får vara det samma på både webbversionen och den mobila versionen men skillnaden att regioner som hade flera bilder i bredd på webbversionen görs om till vertikala regioner. Där mobilversionen oftast har endast en eller max två bilder i bredd på skärmen. Visit Norway hade dock gjort om sin layout i den aspekten att istället för att stapla bilderna på varandra vertikalt hade man möjlighet att swipa (klicka eller dra fingret horisontellt), dvs i deras mobila version kunde man inte bara "skrolla" vertikalt utan på vissa ställen även horisontellt.

En annan intressant aspekt gällande länkar är att alla har någon form av visuell effekt när man för muspekaren över en länk på deras webbversion. Men på deras mobilversion är den visuella effekten i stället när man trycker på en länk.

Alla tre webbplatser hade avsevärt lägre poäng på PageSpeed för deras mobila versioner, oftast hälften eller mindre av poängen de fick för sin webbversion. Om man följer PageSpeeds rekomendationer tyder detta på att många webbplatser har mycket att arbeta på för att besökare skall få en bra upplevelse inte bara på deras webbversioner utan även på deras mobila versioner. Det vanligaste problemet enligt PageSpeed är att det tar alldeles för många sekunder innan en besökare på de mobila versionerna lyckas ladda klart webbplatsen till den grad att alla aspekter av webbplatsen är klara att interageras med.

Referenser
-----------------------
- [Full page screen capture](https://mrcoles.com/full-page-screen-capture-chrome-extension/)
- [PageSpeed Insight](https://developers.google.com/speed/pagespeed/insights/)
- [Visit Sweden](https://visitsweden.com/)
- [Visit Norway](https://www.visitnorway.se/)
- [Visit Britain](https://www.visitbritain.com/)

Övrigt
-----------------------
Jag som skrivit denna rapport heter Stefan Liström och rapporten är ett [uppdrag](https://dbwebb.se/kurser/design-v2/kmom10#k2) från organisationen Valfrihet.
