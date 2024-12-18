Utvärdering av webbplatsers laddningstid och användbarhet
=======================

Denna rapport behandlar webbplatsers laddningstid och användbarhet. I rapporten granskas tre hemsidor med olika innehåll och målgrupper. 


Urval
-----------------------

I denna rapport har jag valt att jämföra de tre mest besökta hemsidorna i sverige. Dessa är wikipedia.org, youtube.com samt facebook.com. Hemsidorna har varierat innehåll som förhoppningsvis ger ett nyanserat resultat.


Metod
-----------------------

För att hitta de tre mest besökta hemsidorna i sverige använde jag mig av hemsidan computersweden.se ([computersweden.se](https://computersweden.se/article/1282738/har-ar-de-100-sajter-som-far-mest-trafik-fran-google-i-sverige.html)). För att utföra jämförelsen av hemsidorna använde jag Google Pagespeed. Jämförelserna utfördes på både desktop och mobil. För att analysera laddningstiderna utnyttjade jag även studiematerialet länkat på dbwebb.


Resultat
-----------------------

Mätningarnas data finns samlat i detta google kalkylark för samtliga hemsidor: [kalkylark](https://docs.google.com/spreadsheets/d/1fyulIAEqGdBrcaf70hI3Oi5ZTpEOZw92Xkb1jMJgktU/edit?pli=1&gid=0#gid=0)



WIKIPEDIA:
Länk till wikipedias hemsida: [www.wikipedia.org](https://www.wikipedia.org/)

![Hemsida](https://www.dropbox.com/scl/fi/bjnmnvcuppogj6py0hel6/wiki.PNG?rlkey=i29v9cu9mg96f49lb70pgug7s&st=ei5d0gss&dl=0&raw=1)


<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS_YpYY9GXl1cXTE89YfOOT9RRlaX82ZvGun4bF1x6Tx9nU-7oMAbw6CNFbsgAT3T_s10i4Z7xVl707/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"class="iframe-style"></iframe>

Wikipedia får överlag ett bra betyg enligt google pagespeed. Det som skulle kunna optimeras är bland annat att minska storleken på DOM-elementet och sätta bestämd width och height på bilderna som används. Detta skulle bidra till att hemsidan får en snabbare laddningstid.


YOUTUBE:
Länk till youtubes hemsida: [www.youtube.com](https://www.youtube.com/)


![Hemsida](https://www.dropbox.com/scl/fi/jey8rblqqrdyzgw0twr9j/youtube.PNG?rlkey=awlz9h4mcerbfnm907ribww6d&st=f7j6c4wa&dl=0&raw=1)


<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS_YpYY9GXl1cXTE89YfOOT9RRlaX82ZvGun4bF1x6Tx9nU-7oMAbw6CNFbsgAT3T_s10i4Z7xVl707/pubhtml?gid=24102545&amp;single=true&amp;widget=true&amp;headers=false"class="iframe-style"></iframe>

Youtubes hemsida får ett något sämre resultat än wikipedia. För att förbättra laddningstiden kan man bland annat rensa bort oanvänd javascript och CSS. Det verkar som att youtube har många inbyggda funktioner som inte är kritiska för att websidan ska fungera, både javascript och CSS kan med fördel ses över för att optimera laddningstiden.


FACEBOOK:
Länk till facebooks hemsida: [www.facebook.com](https://www.facebook.com/)


![Hemsida](https://www.dropbox.com/scl/fi/tc58no9gdw3ti6e5fbrqo/facebook.PNG?rlkey=cuce2nia2t3f4fxun3jvr33u8&st=p7zzpv3b&dl=0&raw=1)



<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS_YpYY9GXl1cXTE89YfOOT9RRlaX82ZvGun4bF1x6Tx9nU-7oMAbw6CNFbsgAT3T_s10i4Z7xVl707/pubhtml?gid=2083152793&amp;single=true&amp;widget=true&amp;headers=false"class="iframe-style"></iframe>

Facebook har bra laddningstid, dock finns det förbättrningar kring att rensa onödig javascript samt ta bort "render-blocking resources". Även på facebooks hemsida kan bilderna med fördel använda en fast width och height för att minska laddningstiden.


Analys
-----------------------

Efter att ha granskat resultaten och sett över förbättringar som skulle kunna implementeras på hemsidorna, har jag insett att det skiljer väldigt lite mellan hemsidorna. Wikipedia hade den snabbaste laddningstiden följt av facebook och därefter youtube. Hemsidorna har fått liknande förbättringsförslag, däribland att rensa upp oanvänd javascript/CSS, sätta bestämd height och width på bilderna samt minska storleken på DOM. Wikipedia och Facebook har inte lika många element på sina webbplatser som youtube, detta har troligtvis en påverkan på laddningssidorna också. Om jag skulle sätta en gräns för vad jag uppfattar som "långsamt" gällande laddningstider, så drar jag gränsen vid youtubes hastighet. Youtube har en laddningstid på ca 5.5 s, så min gräns bör gå vid ungefär 6 s. Jag tycker att samtliga webplatser som jag valde att jämföra har en snabb laddningstid. De är de mest besökta i Sverige, och jag skulle inte tro att det är många som uppfattar någon av hemsidorna särskilt långsam.


Referenser
-----------------------

Föreläsningar från kursen och material från dbwebb användes som referenser i denna rapport.

Övrigt
-----------------------

Jag, Cornelia Björn, skrev denna rapport på egen hand.