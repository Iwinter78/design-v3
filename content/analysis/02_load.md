---
Template: technology
---

Optimering av webbplatser och dess påverkan
=======================

Denna rapport handlar om ett antal webbsidor där deras laddningstid och användbarhet har analyserats med hjälp av diverse verktyg.

Urval
-----------------------

Urvalet är gjort på baserat på de tidigare webbplatser som gjordes i tidigare rapport. I detta fall så kommer att mätningarna att ske på Ikea, Discord och Icas webbplats och undersidor ifall detta behövs.

Metod
-----------------------

För att kunna undersöka webbplatsens laddningstid så har webbplatsen PageSpeed Insights används för att kunna få ut ett flertal värden om webbplatsen som undersöks. Bland annat för att kolla hur pass tillgänglig sidan är på både en dator och på en mobil enhet. Laddningstiden kommer även att undersökas ytligare genom att kolla genom konsolen i webbläsaren för att kunna få ut hur långt tid det tar för webbläsaren att läsa in sidan. För att anteckna observationerna så används Microsoft Excel för att kunna skriva ner observationerna för respektive sida. 

Analys
-----------------------

<h1>Discord</h1>
<img src="../assets/img/discord.png"></img>

Tittar vi på Discord mätvärden så kan vi se att de ligger rätt så bra till på vad det gäller tillgänglighet, bästa praxis och SEO där de nästan får toppoäng i dessa kategorier på datorvarianten av deras webbplats. Någonting som de faller på är prestanda där de får 77/100 av Google Pagespeed. Dock så är inte Discord ensamma om detta då vi kan se i på de andra webbplatserna att även de faller på prestanda kategorien. Detta är dock vi kommer att ta upp senare i denna rapport. Tittar man på laddningstiden så ligger den i snitt på 2 sekunder. Detta förutsatt att man aldrig har besökt sidan och inte har sidan sparad i cacheminnet. Tittar vi vidare på storleken på sidan så är den ca 10 MB. Detta kan vara också en av anledningarna till att sidan tar den tid den tar för att ladda in. Paketen som den laddar in är inte direkt utöver det vanliga i det här fallet då de laddar in 41st. Kollar man på prestandan på en mobil enhet så ser det ungefär ut samma där med den stora skillnaden att storleken på hemsidan är ungefär 3 gånger mindre än datorvarianten men tar ungefär lika långt tid att ladda in som den går på dator varianten.

Mobilvarianten av webbplatsen laddar även in färre paket än datorvarianten. Detta kan vara med anledningen att det finns paket på datorvarianten som inte finns på mobilvarianten då de inte är nödvändiga på en mobil enhet. Det som går direkt att se att det är främst deras JavaScript filer som står för majoriteten av laddningstiden. Så vad de hade kunnat göra är att försöka optimera koden så gott som de går utan att förlora någon funktionalitet. 

<h1>Ikea</h1>
<img src="../assets/img/ikea.png"></img>

Observationen som gjordes på Ikeas webbplats var att den också presterar och rätt bra enligt Google Pagespeed där även den har god tillgänglighet, bra praxis och SEO dock så faller även deras webbplats när det kommer till prestandatestet där den för 67/100 på datorvarianten och 60/100 på mobilvarianten. Ikeas webbplats är väldigt liten där den endast är 3 MB stor och laddar in 42st paket. Laddningstiden i snitt för sidan är 730ms vilket kan vara en god indikation på att sidan är välgjort och väl optimerad vilket även skapar en bra upplevelse för användaren. 
Vid observationen av deras mobilvariant av webbplatsen så är det även där nästan identiska resultat på alla tester. För att kunna förbättra deras prestanda så hade de kunnat ta och ta bord en mängd med JavaScript som inte används. Detta då enligt Google PageSpeeds egen analys av hemsidan. De kan även förbättra sidan genom att anpassa storlekarna på bilderna som de använder beroende på hur snabb uppkoppling en användare har samt vilket typ av enhet de använder sig av. 

<h1>Ica</h1>
<img src="../assets/img/ica.png"></img>

Vid observationen av Icas sida så följer även de ungefär samma mönster som resterande webbplatser har gjort när Google PageSpeed har gjort sin analys av webbplatsen. Kollar vi laddningstiden så kan vi se att det tar ca 2 sekunder att ladda in sidan på borde datorversion och mobilversionen. Någonting som stack ut var antalet paket som sidan laddar in på både datorversionen och mobilen. Där det laddandes in 83st paket på datorvarianten respektive 77st på mobilen. Detta var väldigt underligt då sidan laddar in nästan dubbelt så många paket jämfört med resterande webbplatser som har observerats. Tittar vi på storleken så är sidan ca 6MB stor på båda datorvarianten och på mobila enheter.

Områden som hade kunnat förbättrats på webbplatsen är främst att webbplatsen laddar in JavaScript som inte används när sidan laddar in för första gången. Någonting annat som påverkar prestandan av webbplatsen är att det finns resurser som laddar in på den som hindrar sidan från att ladda in. Detta är någonting som kan orsakas av event som triggas på webbplatsen när den laddar in.


Resultat
-----------------------

Efter att ha observerat dessa sidor så har jag kommit fram till att är att de ändå verkar vara väldigt sparsamma när det kommer till de resurser som krävs från användarens sida för att kunna använda deras hemsida. Detta baserat på att alla sidor ändå använder sig av bra praxis. Vilket kan vara en indikation på att de ändå försöker hålla en god standard på deras webbplats. Någonting som kan tillföra bättre prestanda på hemsidan. De vanligaste problemen som alla webbplatser som har observerats verkar främst ha problem med att de laddar in event som hindrar från att resten av sidan laddas in ordentligt förens antingen eventet är över eller om användaren kan påverka eventet. Ett annat problem som upptäcktes rätt ofta var att webbplatserna laddar in JavaScript kod som inte används när sidan laddar in. 
Det bör även noteras att det var samma problem på datorvarianterna av webbplatsen som det var för de mobila varianterna. 
Om jag skulle få lov att rangordna dessa tre webbplatser som har observerats så skulle det se hur så här: 

<img src="../assets/img/winner_load.jpg"></img>

Referenser
-----------------------

<iframe width="402" height="346" frameborder="0" scrolling="no" src="https://studentbth-my.sharepoint.com/personal/seol23_student_bth_se/_layouts/15/Doc.aspx?sourcedoc={dd9bd0a8-8aa4-4b34-936a-ae6fc7e1d2db}&action=embedview&wdAllowInteractivity=False&wdHideGridlines=True&wdHideHeaders=True&wdDownloadButton=True&wdInConfigurator=True&wdInConfigurator=True"></iframe>

Discord. <a href="https://discord.com/"><p>https://discord.com/</p></a>
Ica. <a href="https://www.ica.se/"><p>https://www.ica.se/</p></a>
Ikea. <a href="https://www.ikea.com/"><p>https://www.ikea.com/</p></a>
<a href="https://www.bluecorona.com/blog/how-fast-should-website-be/"><p>Bluecorona. 2019. How fast should a website load? (2023-11-30) </p></a>

Övrigt
-----------------------

Rapporten är skriven av Sebastian Olausson