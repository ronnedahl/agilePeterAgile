# Individuella reflektioner

Svara på var och en av frågorna nedan individuellt (minst 80 tecken per fråga)

## Frågor

### Inledning

#### Vad var ditt mål med projektet initialt?
Att vara med och arbeta i ett team med ett gemensamt mål. Att gå från en figma-skiss till en färdig produkt och 
lära sig att använda kod på ett så bra sätt som möjligt.Både strukturmässigt och funktionsmässigt.

#### Hur upplevde inför arbetet att arbeta i team?
Man fick en stor inlick hur arbetslivet kommer att te sig i framtiden. Vi tappade tyvärr en i vårt team och insåg då hur
beronde man är av varandra i ett större projekt och att våra möten ett produktivt samarbete. 

### Planering och genomförande

#### Hur tycker du att planeringen inför projektet fungerade?
Nu i efterhand skulle man för egen del ha gjort ett flödeschema innan den första sprint plannen. Vi skulle även ha gjort beskrivningarna på features tydligare och även delat upp dem i ännu mindre delar.

#### Vad har du bidragit med i planeringen, samt utvecklandet av applikationen.
Jag var med på sprint plannen tillsammans med teamet och kom med förslag och funderingar. Jag har deltagit i alla möten som vi har haft och löst små och lite större uppgifter.


#### Beskriv med dina egna ord, er applikation
applikationen börjar med en landningssida där en hamburger-meny finns i det vänstra övre hörnet.
En lyssnare triggas när besökaren trycker på hamburgermenyn och det rullas ned en meny med 100vh och 100% width.
det går nu att göra 4 val. Väljer du meny kommer du till en meny med olika kaffesorter. 

Meny renderas ut från funktionen renderShoppingCart och med hjälp aven foreach som itererar över localstorage 'cart' innehåll. Elementen skapas sedan i javascript och en lysnnare på plusknappen som leder till en funktion som ändrar antalet beställninar på kaffesorten. I det högra hörnet kan du nu även se hur många beställninar som har gjorts och när du trycker på iconen renderas en meny från functionen rendershoppingModal(). I detta fönster kan du välja om du vill öka antalet beställningar eller minska beställningen med hjälp av lysnnare på upp och ned pilarna samt att detta justeras i localstorage. trycker man sedan på take my money knappen kommer du till en status sida där ett slumpat tal mellan 15-20 minuter. Ett unikt ordernummer skapas i functionen generateUniqueOrderNumber().

En about sida med "Vårt Kaffe" kan väljas vilket leder till en enkel html.sida med html och css kod.
Du kan välja på om du redan har registrerat dig att logga in med din email adress och lösenord. Lösenordet och emailadressen kontrolleras 
i localstorage och kollar om emailadressen finns och username i user.js . Checkboxen GDPR Ok måste vara itryckt för att vi ska komma vidare.
När man blivit inloggad renderas en annan meny som bara visas för den inloggade användaren. Är du admin visas en annan meny som renderas från render.js 

Som admin kan man ta bort eller lägga till en kaffesort. Möjlighet finns också att ändra produktnamn,pris samt beskrivning . Man kan även registrera sig som ny användare där kontroll görs i localstorage om användarnamnet eller lösenordet redan finns. Finns det ej sparas detta i localstorage. Som registrerad användare kan man få en order history som visar vad som du har handlat tidigare.Du kan även ändra username,email och password som user som sedan sparas i localstorage när lyssnaren gör om mig clickas  på.



### Teamets utmaningar och lösningar

#### Vika var de största utmaningarna för dig?
github har varit den största utmnaningen när vi har arbetat med brancher, det hände några gånger att man var lite för snabb och pushade till main istället för till dev. Javascript är svårt , men desto mer man håller på med det desto lättare går det. 

#### Hur löste eller hanterade du dessa utmaningar?
Jag tog hjälp av teamet och då i synnerhet kim som var vårat "ankare". Vi gick lugnt och metodiskt igenom
problemen som uppstod och hanterade dessa med bravur.
#### Vilka kompromisser inom teamet har du fått göra under projektets gång?


### Individuell reflektion och utvärdering

#### Vad lärde du dig under projektets gång?
jag lärde mig hur man arbetar i team och att ta hjälp tidigare , istället för att försöka att 
lösa uppgiften själv om man har fastnat i koden och febrilt försöker att felsöka i koden.

#### Finns det någonting du skulle velat göra annorlunda om du fick chansen igen?
jag skulle ha avsatt tid för att göra ett grundligt och genomtänkt flödesschema för att 
kunna förstå vilka funktioner som behövs och var funktionerna skall vara placerade.
Jag skulle ha börjat med en lättare uppgift först och inte gått på en av de svårare i början.

#### Vilka möjligheter ser du med de kunskaper du fått under arbetet med projektet?
Jag tyckte det var ett bra projekt eftersom det var väldigt verklighetsförankrat samt att 
arbeta med varukorg system av olika typer kommer att ingå i det framtida arbetet.
antingen som konsult eller ingå i ett större företag kommer dessa kunskaper vara till stor nytta.



### VG-frågor

#### Vilka fördelar ser du med att arbeta agilt?
(insert answer here...)

#### Motivera varför du föreslagit en specifik lösning
(insert answer here...)

#### Beskriv exempel på lösningar du ansåg INTE SKULLE implementeras och varför
(insert answer here...)

#### Reflektera kring hur den kod du bidragit med skulle kunna förbättras
(insert answer here...)

#### Reflektera kring hur ert arbete skulle kunna förbättras
(insert answer here...)

