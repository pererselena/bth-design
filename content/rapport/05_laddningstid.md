---
---
Laddningstid
=========================

Denna uppgift handlar om att välja ut ett antal olika webbsidor och analysera deras laddningstid. Jag ska redogöra för vad man kan förbättra med avseende på laddningstid.

Urval
-----------------------

Jag har valt att analysera de tre största resebyråerna. Jag har valt dessa då de har många bilder på sina sidor. Det kan vara intressant att se hur de presterar vad gäller laddningstid.

[Apollo](https://www.apollo.se/)
[Tui](https://www.tui.se/)
[Ving](https://www.ving.se/)

Metod
-----------------------

Jag har använt developer tools i Chrome för att analysera sidorna. Jag har även använt PageSpeed Insights för att få en analys och förslag till förbättringar av laddningstid. Jag har även använt mig av boken "The principles of Beautiful Web Design".

Resultat
-----------------------
Här finns mitt [Excel ark med testdata](https://1drv.ms/x/s!Aojs1_-BoQ6wh_YfnXCbm6dzy9hh-A).

Här följer de resultat jag hittade per webbplats.

##Apollo:

[FIGURE src="image/rapport/apollo.jpg?w=300&h=400" caption="Bild på Apollos webbsida" class="left"]

Resultat från min mätning ger Apollo ett medelvärde av 2,47 sekunder av sin första sida. Deras rese sida laddas på 2,6 sekunder medans deras sida med erbjudanden laddas på 4,46 sekunder.
I mobilt läge laddas sidorna istället på 3,77 sekunder för första sidan, Resa på 2,25 sekunder och erbjudande på 2,92 sekunder.

Generellt är storleken på sidorna större i mobilt läge och laddningstiden varierer på de olika sidorna för mobilt eller desktop. Antalet resurser är liknande i båda mobilt och desktop.

PageSpeedInsights:  
[Start](https://www.apollo.se) Mobilt: 39 Dator: 98  
[Resa](https://www.apollo.se/resa) Mobilt: 61 Dator: 100  
[Erbjudande](https://www.apollo.se/erbjudanden) Mobilt: 60 Dator: 100

De vanligaste föreslagna ändringarna till Apollo är att läsa in viktiga resurser i förväg, koda bilder effektivt, skjut upp inläsningen av bilder som inte visas på skärmen, ta bort resurser som blockerar renderingen och att använda modernare bildformat samt att använda bilder i rätt storlek.



##Tui

[FIGURE src="image/rapport/tui.jpg?w=300&h=400" caption="Bild på Tuis webbsida" class="right"]

En intressant notiering jämfört med alla andra resebolag var att finish tid och storlek samt requests tickar upp ju längre tid man har sidan öppen.

Laddningstiden är lite längre i mobilt läge jämfört i desktop, förutom för erbjudande sidan. Storleken på startsidan är större i mobilt läge, men övriga sidor är större i desktop. Överlag är antalet resurser lägre i mobilt läge förutom för start sidan där det återigen är omvänt..

PageSpeedInsights:  
[Start](https://www.tui.se/) Mobilt: 61 Dator: 100  
[Resa](https://www.tui.se/resa) Mobilt: 45 Dator: 97  
[Erbjudande](https://www.tui.se/erbjudanden) Mobilt: 66 Dator: 100

De vanligaste föreslagna ändringarna till Tui är att ta bort resurser som blockerar renderingen och skjuta upp CSS som inte används och att de ska skjuta upp inläsning av bilder som inte visas på skärmen. Generellt har de bäst laddningstider.

##Ving

[FIGURE src="image/rapport/ving.jpg?w=200&h=300" caption="Bild på Vings webbsida" class="left"]

Ving har generellt stor storlek på sina sidor, däremot är mobilt mindre än desktop. Laddningstid är även det lite mindre än för desktop. Resuser är ungefär likadant för både mobilt och desktop.

PageSpeedInsights:  
[Start](https://www.ving.se/) Mobilt: 35 Dator: 96  
[Resor](https://www.ving.se/resor) Mobilt: 31 Dator: 97  
[Erbjudande](https://www.ving.se/erbjudanden) Mobilt: 58 Dator: 100

Den vanligaste föreslagna ändringarna för ving är att använda bilder i modernare bildformat eller i alla fall mindre format och storlek.

Dom rekommenderas även att ta bort resurser som blockerar renderingen och att fördröja laddningen av CSS som inte används.



Analys
-----------------------

Den webbplats med sämst resultat var Ving. Dom måste framförallt förbättra sin mobilsida. Det tar mycket tid och sidorna är störst hos Ving.
Alla webbplatser bör förbättra sina mobil sidor, skillanden i storlek och laddningstider mellan desktop och mobilt är generellt inte alls märkbar.

Alla webbplatser använder <picture> och olika bilder till olika enhter vilket är bra.
Alla sidor behöver arbeta med vilka bildformat och storlekar som de använder. Samt att se över vilka resurser som laddas in och i vilken ordning. Man har den del CSS och andra resurser som inte visas eller blockerar laddning utav sidorna.
Det bästa resultatet fick tui men PageSpeedInsights tycker att de har mycket att förbättra vad gäller deras mobila sida vilket inte märktes så väl i mitt test.

En laddningstid på under två sekunder upplever jag som snabbt för en sida som har många bilder. Ligger man över 3 sekunder så tycker jag att man ligger för högt.
Enligt detta så klarar Tui sig bra, Apollo är nästan där medans Ving har mycket att jobba med.
Rent generellt uppleves Tui som snabbast och de övriga ligger på gränsen till vad man vill acceptera.

Referenser
-----------------------

[PageSpeedInsights](https://developers.google.com/speed/pagespeed/insights/)  
[Moz Page Speed](https://moz.com/learn/seo/page-speed)

Kurslitteratur:

Titel: The Principles of Beautiful Web Design
Utgiven, revision, antal sidor: 2014, Third edition, 220s
Författare: Jason Beaird
Förlag: SITEPOINT
ISBN: 9780992279448

Övrigt
-----------------------

Rapport gjord av Elena Perers.
