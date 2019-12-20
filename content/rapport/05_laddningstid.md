---
---
<DIV class="report">
Kmom05 laddningstid
=========================
</DIV>

Denna rapport kommer utvärdera och analysera tre olika politiska partiers webbplatser och dokumentera deras laddningstider samt argumentera kring valet av resurser och potentiella förbättringar som skulle kunna göras.

Urval
-----------------------
Jag har gjort denna övning själv och jag valde att utvärdera politiska partier för att jag är intresserad av politik och tänkte att jag nu kan kombinera det intresset men att utvärdera hur olika partier hanterar deras digitala närvaro.

Jag valde att utvärdera de tre partier som fick flest röster i senaste valet. Jag tänker att de då har en likvärdig status och att jämförelsen mellan deras sidor blir intressant för att se ifall organisationer med liknanden status har lyckats göra något annorlunda gällande deras webbplatser.

De tre partier jag valde att utvärdera blev med andra ord [Socialdemokraterna](https://www.socialdemokraterna.se/), [Moderaterna](https://moderaterna.se/) och [Sverigedemokraterna](https://sd.se/).

Metod
-----------------------
Som metod för att skriva denna rapport utgick jag ifrån kraven i uppgiften och utvärderade och analyserade webbplatserna baserat på de aspekter som rapporten skulle innehålla, dessa var primärt:

- Mäta pagespeed på tre sidor på varje webbplats med hjälp av Google Pagespeed.
- Mäta pagespeed på både mobile och desktop och notera resultaten.
- För varje ovan sida kontrollerade jag även devtools flik networks och noterade sidornas laddningstider tillsammans med antalet resurser som laddas samt sidans totala storlek. För varje sida gjorde jag mätningen tre gånger och tog snittet av mätvärdena. Jag säkerställde att jag inte använda sparade resurser i cashen för att få korrekta mätresultat.
- Mätvärdena sparade jag i [Google sheets](https://docs.google.com/spreadsheets/d/1pJyawXcO14wmDpg-EQeDY6BpnXOxhuK7Or_zrrD8Hrg/edit?usp=sharing).

De tre sidor jag valde att mäta för varje partis webbplats var förstasidan, sidan som innehöll information om deras politik och deras pressida.

För att ta en bild på hela förstasidan på webbplatsen använde jag tillägget [Full page screen capture](https://mrcoles.com/full-page-screen-capture-chrome-extension/) till Chromes webbläsare. Detta tillägg gjorde det möjligt att på ett enkelt sätt ta en bild på deras webbplats i ett steg trots att man behöver scrolla ner över flera skärmlängder för att se hela webbplatsen.

Resultat
-----------------------
### Socialdemokraterna
#### Skärmbild från Socialdemokraternas webbplats

[FIGURE src=img/socialdemokraterna.png caption="Förstasidan på Socialdemokraternas webbplats."]

#### Resultat
Socialdemokraternas tre sidor hade följande laddningstider (i snitt) och poäng från Google Pagespeed.
|                                   Sida                            |Laddtid | Mobile poäng | Desktop poäng|
|-------------------------------------------------------------------|:------:|:------------:|:------------:|
|[Förstasidan](https://www.socialdemokraterna.se/)                  | 1,37s  | 6            | 44           |
|[Deras politik](https://www.socialdemokraterna.se/var-politik)     | 1,54s  | 8            | 49           |
|[Press-sidan](https://www.socialdemokraterna.se/vart-parti/press)  | 1,36s  | 9            | 55           |

För kompletta mätresultaten se [Google sheets](https://docs.google.com/spreadsheets/d/1pJyawXcO14wmDpg-EQeDY6BpnXOxhuK7Or_zrrD8Hrg/edit?usp=sharing).

#### Förbättringar
Socialdemokraternas mobilanpassade sida hade absolut sämst betyg av de tre testade. Där har de mycket potential att göra förbättringar. Det som primärt tog upp onödig laddningstid var att de inte använder nästa generations bildformat, textkomprimering och tar inte bort icke använd CSS kod.

Även när det kommer till desktop versionen så får socialdemokraterna relativt dåliga poäng i relation till de andra webbplatserna som testades. Även här handlar det om att de inte använder nästa generations bildformat eller textkomprimering, men även att det finns element (så som javascript) på deras sida som blockerar renderingen av sidan.

### Moderaterna
#### Skärmbild från Moderaternas webbplats
[FIGURE src=img/moderaterna.png caption="Förstasidan på Moderaternas webbplats."]

#### Resultat
Moderaternas tre sidor hade följande laddningstider (i snitt) och poäng från Google Pagespeed.
|                                   Sida                |Laddtid | Mobile poäng | Desktop poäng|
|-------------------------------------------------------|:------:|:------------:|:------------:|
|[Förstasidan](https://moderaterna.se/)                 | 12,05s | 52           | 94           |
|[Deras politik](https://moderaterna.se/var-politik)    | 2,48s  | 78           | 98           |
|[Press-sidan](https://moderaterna.se/press)            | 2,09s  | 75           | 97           |

För kompletta mätresultaten se [Google sheets](https://docs.google.com/spreadsheets/d/1pJyawXcO14wmDpg-EQeDY6BpnXOxhuK7Or_zrrD8Hrg/edit?usp=sharing).

#### Förbättringar
Moderaternas tre sidor hade längsta laddningstiden när man mäter med devtools men samtidigt hade de bästa poängen när man mäter med Google pagespeed. Deras förstasida laddade generellt sett klart på ca. två sekunder, det var dock ett Youtube element som efterladdades och blev inte klart föränn ca 10 sekunder senare, därav deras extremt långa laddtid på förstasidan.

Den förändring som Moderaterna främst skulle kunna göra för att få en snabbare laddningstid är att börja använda nästa generations bildformat.


### Sverigedemokraterna
#### Skärmbild från Sverigedemokraternas webbplats
[FIGURE src=img/sd.png caption="Förstasidan på Sverigedemokraternas webbplats."]

#### Resultat
Sverigedemokraternas tre sidor hade följande laddningstider (i snitt) och poäng från Google Pagespeed.
|                                   Sida        |Laddtid | Mobile poäng | Desktop poäng|
|-----------------------------------------------|:------:|:------------:|:------------:|
|[Förstasidan](https://sd.se/)                  | 1,71s  | 20           | 86           |
|[Deras politik](https://sd.se/vad-vi-vill/)    | 1,77s  | 10           | 80           |
|[Press-sidan](https://sd.se/press/)            | 1,72s  | 16           | 80           |

#### Förbättringar
Sverigedemokraterna hade relativt låga laddnignstider men precis som Socialdemokraterna hade de väldigt låga poäng från Google pagespeed på deras mobilversioner.

De förändringar som Sverigedemokraterna skulle tjäna mest på för att få ner laddtiderna är dels byta till nästa generations bildformat men även att se över storleken på bilderna och skala ner storleken på t.ex. deras mobilanpassade sidor. De skulle även minska laddningstiden ifall de tog bort element som hindrar renderingen av sidorna så som vissa javascript.

Analys
-----------------------
Alla tre sidor hade relativt liknande upplägg på hur de presenterade information på deras sidor och det var relativt liknande saker som de kunde förändra för att få bättre laddnignstider.

Den stora skillnaden låg i hur de hanterade informationen de presenterade. Både Socialdemokraterna och Sverigedemokraterna fick väldigt låga betyg på deras mobilanpassade sidor, främst p.g.a. att de inte hanterade bilder på ett för mobiler bra sätt. Dels använde de inte nästa generations bildformat och Sverigedemokraterna skulle kunna se över skalan på bilderna de presenterar för mobiler. Det som var intressant var dock att det var Moderaterna som hade långsammaste laddnignstiderna i devtool, men det kan bero på att jag inte simulerade en mobiltelefon i de testerna.

De vanligaste förbättringspotentialerna var i stort sätt lika för alla tre sidor, nämligen att börja använda nästa generations bildformat, se till så att de inte har element som javascript som blockerar renderingen av sidorna, att börja använda textkomprimering och att ta bort icke använd CSSkod.

### Rankning
Baserat på poängen i ovan tester rankar jag partiernas webbplatser på följande sätt:

1. Moderaterna
2. Sverigedemokraterna
3. Socialdemokraterna

Moderaterna vinner främst p.g.a. att de har anpassat sin webbplats för både mobil och desktop användning, det är något som varken Sverigedemokraterna eller Socialdemokraterna verkar ha fokuserat på i deras webbplatser. Det sagt så finns det fortfarande en del saker Moderaterna har möjlighet att förbättra. Så det känns som att Moderaterna vinner p.g.a. att deras motståndare var så dåliga, snarare än att de själva var bra.

### Snabb webbplats
För min egen del så tycker jag alla webbplatser som inte går att börja använda efter en sekund är en dålig webbplats (ur laddnignsperspektiv). D.v.s. jag förväntar mig när jag sitter vid en desktop med "bra" Internet att jag skall kunna börja scrolla runt på en webbplats en sekund efter att jag kommit in på sidan. Att vissa element på sidorna fortsätter att ladda och att hela sidan tar över en sekund tycker jag oftast är okey, så länge det inte är element som laddas som hindrar mig väsentligt från att använda sidan i fråga. När jag använder en mobil för att surfa på webbplatser har jag lite mer överseende på att det tar tid att ladda en webbplats, men även där skulle jag börja bli irriterad ifall det tar mer än två sekunder från det att jag laddar en sida till att jag kan börja använda den, dvs scrolla runt och klicka på element på sidan.

Jag tycker alla tre webbplatser klarade av att leverera en funktionsduglig sida inom en sekund när jag använde min desktop. Däremot så var både Socialdemokraterna och Sverigedemokraterna på gränsen till att vara irriterande långsamma att ladda första sidan när jag surfade till deras sidor på min mobil.

Referenser
-----------------------
[1] [Google sheets med mätdata](https://docs.google.com/spreadsheets/d/1pJyawXcO14wmDpg-EQeDY6BpnXOxhuK7Or_zrrD8Hrg/edit?usp=sharing)

Övrigt
-----------------------
Jag som skrivit denna rapport heter Stefan Liström och rapporten är en del av uppgifterna i kursmoment 5 (kmom05) i webbprogrammeringskursen design på BTH.
