## Mål
Att de ska introduceras till grupper som ett verktyg att se på världen, och finna de fina symmetrier som grupp gruppstrukturer 

Vill vi ha en geografisk tolkning?


## Viktiga mål att lära ut:
- Lagrange teorem
- Klassgrupper, vi ignorerar något
- Normala grupper
- Cykliska grupper
- Gruppverkan?


För Lagrange teorem krävs:
- Vad är en grupp
- Hur grupper beter sig
- Många exempel
- Delgrupper
- Kan multiplicera mängder med element
- Kan multiplicera delgrupper med element
- Sidoklasser med en ekvivalens relation
- Samma antal element samt distinka eller samma
- Lagrange teorem



Bra exempel på grupper:
- Symmetrier
- Rubiks kub
- Hänga tavla så att den försvinner med ett snöre


# Tankar
- Vore kul att få det att handla om hur man skulle kunna beskriva saker vi ser i vår omvärld
    - Att man vill beskriva symmetrier och liknande handlingar
- I symmetrier handlar det ofta om själva handlingen snarare än positionen
- Man skulle kunna påpeka hur algebran är ett väldigt trevligt sätt att beskriva saker, kanske med hur det fungerar
- Tema: Kardinaliteten av gruppen
    - Lagranges Teorem
    - Eulers sats / Fermats Lilla sats
    - Burnsides lemma
- Syftet är a generalisera och abstrahera


# Lektionsinnehåll
- Lektion 1: Introduktion av centrala begrepp och beskrivning
    - Vi önskar beskriva vissa typer av saker:
        - Heltals addition
        - Rubrikskub rörelser
        - Permutationer
        - Symmetrier
    - Vill beskriva likt med algebra:
        - Har en mängd med element
        - En operation på dessa
        - Vilka krav sätter vi?
    - Detta ger oss ett språk att arbeta med
    - Problem om grupper och operationerna på:
        - Bevisa flera små saker
        - Sätt upp en tavla så att om en faller, gör för oändligt många
        - Rubikskub operation leder alltid tillbaka till samma

- Lektion 2: Lagrange teorem
    - Delgrupper
    - Multiplikation av mängder
    - Sidoklasser
    - Har samma antal element
    - Är disjunkta eller samma
    - OBS! Presentera resultatet och ungefära vägen först
    - Applikationer: Bevisa Eulers sats
    - Massa trevliga saker
    - Fortsätt från tidigare
    - Kanske normala grupper och sidoklasser?
    - Fermats sats

- Lektion 3: 
    - Gruppverkan
    - Kör upp till Burnsides

- Lektion 4:
    - En fin sak är att när vi känner till strukturen, kan vi hitta liknande
    - Till exempel, symmetrier hos en triangel, och symmetriska gruppen för tre punkter
    - Introducerar homomorfismer och dess varianter
    - Visa huruvida olika är isomorfa och liknande (typ Q under addition vs Q \ {0} under multiplikation
    - Introducera cyklisk genom detta?
    - Rubikskub problem
    - Hur är det kopplat till antalet element?, Kernel och image

- Cykliska grupper, Fermats sats, deras delgrupper och chinese remainder theorem?
- Gruppverkan, burnsides lemma
- Applikationer!
Homomorfismer!





# Tankar
- Vore nice med ett konkret motiverande problem till varje lektion, så kan man låta alla försöka lösa det, men sedan gå igenom teorin
- Vore kul med en fysisk grej man kan ta med till alla lektioner









# Lektionsplan Gruppteori (Gammal)
(+ är genomgång, - är problem eller bevis deltagarna gör, vid motiverande problem får de försöka lösa men efter några minuter börjar genomgången)

Målet jag tänker med kursen som helhet är att ge grupper som ett verktyg att förklara fenomen med, få se och bevisa några centrala satser, och bekanta deltagarna lite med abstrakt algebra.

Kursen skulle kunna vara strukturerad ungefär:
1. Introduktion till grupper med exempel och kopplade problem
2. Bevisa Lagrange teorem
3. Gruppverkan & bevisa Burnsides lemma
4. Utrymme för fortsättning från tidigare, annar homomorfismer mellan grupper

Tanken är alltså att deltagarna ska bevisa de större satserna med ledning från problemen.

## Lektion 1: Grupper som verktyg, introduktion till centrala begrepp och exempel
Målet är att introducera gruppteori som koncept och de grunder som krävs för senare, samt att visa att det är ett användbart sätt att beskriva fenomen på.

+ Motiverande problem: Visa att inget "drag" på en rubiks kub kommer gå igenom alla möjliga

+ Vi önskar beskriva vissa typer av saker:
    + Heltals addition
    + Rubrikskub rörelser
    + Permutationer
    + Symmetrier
+ Vill beskriva likt med algebra:
    + Har en mängd med element
    + En operation på dessa
    + Vilka krav sätter vi?
+ Detta ger oss ett språk att arbeta med
+ Motivera för några exempel att de är grupper

- Låt de motivera varför resterande är grupper, samt motivera varför andra exempel ej är (typ heltalsmultiplikation, projektioner, addition med tal inte delbara på 3)
- Låt de bevisa olika små satser typ
    - Enhetselementet är unikt
    - (ab)^-1=b^-1a^-1
    - ab = cb => a = c
    - Inversen är unik
    - Vänsterinvers & Vänsteridentitet => Grupp
    - Intersection of two groups is a group
- Bevisa saker om verkliga ting:
    - Rubikskub:
        - Fortsatt applicering av ett drag leder alltid tillbaka till ursprungspositionen
        - Inget drag, som fortsätter appliceras kan leda till alla konfigurationer (nämn cyklisk)
        - Kan samma appliceras på blandningar av en kortlek?
    - Snören:
        - Du önskar hänga en tavla på två skruvar så att om någon skruv tas bort försvinner tavlan
        - Beskriv med grupper
        - Om du ska ha 3, 4, eller 5, hur generaliserar du då?
    - Fler saker?
- Flera kluringar? Osäker på om det här materialet räcker för en lektion.

## Lektion 2: Lagranges teorem
Målet är att deltagarna ska bevisa Lagrages teorem (storlek på ändlig grupp delas av storlek på delgrupp), då det är ett väldigt coolt och ganska intutivt koncept som är användbart på många platser. De får även applicera det på bland annat Eulers sat i talteorin

+ Motiverande problem: Bevis av Eulers sats

+ Delgrupp är en grupp inom en annan grupp
+ Exempelvis jämna heltal under addition, rotationer i dihedral grupper

+ Formulera Lagranges Teorem
+ Motivera intuition
+ Målet är att deltagarna ska bevisa denna (och sedan applicera den)

- Bevisa Lagranges Teorem
    - Om vi multiplicerar en delmängd med ett element får vi en sidoklass
    - Hur många element har sidoklassen?
    - Finns alla element i någon sidoklass till en delgrupp?
    - När är två "representationer" av sidoklasser samma sidoklass?
    - Kan två sidoklasser dela exakt två element? Vilka antal element kan de dela?
    - Med hjälp av ovanstående, bevisa Lagranges teorem

- Applikationer
    - Bevisa Fermats sats för grupper (viss beskrivning av cyklisk grupp innan)
    - Bevisa Eulers sats med hjälp av Lagranges teorem
    - Visa att om två grupper har relativt prima storlekar så är snittet identitetselementet
    - Andra fina applikationer... osäker på exakt vilka

- Kluring frågor utöver
    - Är mängden sidoklasser en grupp? Annars, vad skulle vi kunna ställa för krav på delmängden för att det ska bli det?
    - Några frågor om normala grupper, och kvotgrupper

## Lektion 3: Gruppverkan och Burnsides Lemma
Målet är att deltagarna ska bevisa Burnside lemma och kunna applicera det då det väldigt inom kombinatoriken med en trevlig geometrisk tolkning

+ Motiverande problem: Hur många 2x2 glasschackbräden kan man göra med k möjliga färger?

+ Här har vi inte riktigt en grupp, utom en mängd objekt som verkas på av en symmetrigrupp.
+ Definition av gruppverkan
+ Definierar burnsides lemma
+ Löser problemet med den

- Lös annat liknande problem med Burnsides lemma

- Enkla identiteter om gruppverkan som uppvärmning

- Definition av en bana
- Bevisa att banorna partitionerar mängden (om banor delar något element delar de alla)
- Definition av stabilisatoro
- Visa storlek på stabilisator gånger storlek på bana är gruppens storlek

- Beviset
    - Önskar räkna par av g och x, så att gx = x
    - Summerar mängden först ger en tolknig
    - Summerar gruppen först sedan mängden = Summan |Stabilisatorn| = Summan av |G|/|Banan| = Summan över antalet grupp |G|
    - Formulera Burnsides lemma

- Applikationer på några problem

- Kluring frågor utöver:
    - Hitta kopplingen mellan gruppverkan och symmetriska gruppen
    - Andra roliga?

## Lektion 4: Catch up, eller homomorfismer
Målet med den här lektion är att ge lite uttrymme för om något behövs från de tidigare. Om det behövs mer material tänker jag att man arbetar med homomorfismer mellan grupper, men detaljerna är lite oklara.

- Motiverande problem: Finns det någon egentlig skillnad mellan (Q, +) och (Q\{0}, *)? Alltså, kan man tänka sig att de beter sig på samma sätt?
- Definition av homomorfismer, epimorfismer, monomorphismer, och isomorphismer
- Ge olika exempel
- En samling problem om att hitta kluriga sådana mella olika saker grupper, typ:
    - Epimorfism från heltal till cyklisk grupp
    - Monomorfism från heltal till jämna (under addition)
    - Från Z^\infty + till rationella tal under multiplikation
    - Cyklisk till andra cykliska eller sig själv
- En samling om att visa att ingen isomorfi kan finnas:
    - Motiverande problemet
    - Dihedral till cyklisk
- Annat som är kopplat?
- Andra kluriga problem från hela kursen?
- Tänker att det lämnas lite fritt för vad man märker är bra under kursens gång.



























# Lektionsplan Gruppteori
(+ är genomgång, - är problem eller bevis deltagarna gör, vid motiverande problem får de försöka lösa men efter några minuter börjar genomgången)

Målet jag tänker med kursen som helhet är att ge grupper som ett verktyg att förklara fenomen med, få se och bevisa några centrala satser, och bekanta deltagarna lite med abstrakt algebra.

Kursen skulle kunna vara strukturerad ungefär:
1. Introduktion till grupper med exempel och kopplade problem
2. Isomorfier och liknande
3. Delgrupper & sidogrupper
2. Bevisa Lagrange teorem

Tanken är alltså att deltagarna ska bevisa de större satserna med ledning från problemen.

## Lektion 1: Grupper som verktyg, introduktion till centrala begrepp och exempel
Målet är att introducera gruppteori som koncept och de grunder som krävs för senare, samt att visa att det är ett användbart sätt att beskriva fenomen på.

+ Motiverande problem: Visa att inget "drag" på en rubiks kub kommer gå igenom alla möjliga
+ Vi önskar beskriva vissa typer av saker:
    + Heltals addition
    + Rubrikskub rörelser
    + Permutationer
    + Symmetrier
+ Vill beskriva likt med algebra:
    + Har en mängd med element
    + En operation på dessa
    + Vilka krav sätter vi?
+ Detta ger oss ett språk att arbeta med
+ Motivera för några exempel att de är grupper

- Låt de motivera varför resterande är grupper, samt motivera varför andra exempel ej är (typ heltalsmultiplikation, projektioner, addition med tal inte delbara på 3)

- Hitta dihedrala grupperna.
    - Hur ser dem ut?
    - Hur kan man beskriva dem?
    - Gör en multiplikationstabell

- Bevisa saker om verkliga ting:
    - Rubikskub:
        - Fortsatt applicering av ett drag leder alltid tillbaka till ursprungspositionen
        - Inget drag, som fortsätter appliceras kan leda till alla konfigurationer (nämn cyklisk)
        - Kan samma appliceras på blandningar av en kortlek?
    - Snören:
        - Du önskar hänga en tavla på två skruvar så att om någon skruv tas bort försvinner tavlan
        - Beskriv med grupper
        - Om du ska ha 3, 4, eller 5, hur generaliserar du då?
    - Fler saker?

- Låt de bevisa olika små satser typ
    - Enhetselementet är unikt
    - (ab)^-1=b^-1a^-1
    - ab = cb => a = c
    - Inversen är unik
    - Vänsterinvers & Vänsteridentitet => Grupp
    - Snittet av grupper är en grupp

- Flera kluringar? Osäker på om det här materialet räcker för en lektion.

## Lektion 2: Homomorfismer, främst Isomorfier
Målet med den här lektionen är att ge förståelse för att vissa grupper liknar varandra väldigt mycket

+ Motiverande problem: Finns det någon egentlig skillnad mellan (Q, +) och (Q\{0}, *)? Alltså, kan man tänka sig att de beter sig på samma sätt?
+ Fråga, vad innebär det att två grupper har "samma struktur"?
+ Definition av homomorfismer och isomorfismer

- En samling problem om att hitta kluriga sådana mella olika saker grupper, typ:
    - Isomorfism från heltal modulo till cyklisk grupp
    - Isomorfism från heltal till jämna (under addition)
    - Från Z^\infty + till rationella tal under multiplikation
    - Cyklisk till andra cykliska eller sig själv
- En samling om att visa att ingen isomorfi kan finnas:
    - Motiverande problemet
    - Dihedral till cyklisk

- Annat som är kopplat?
    - Är Z_2×Z_2 och Z_2×Z_3 är isomorfa med Z_4 respektive Z_6?

## Lektion 3: Delgrupper och sidoklasser
+ Motiverande problem: TODO!
+ Finns ibland mindre strukturer inom
+ Definition av delgrupper

- Hitta kul delgrupper
    - Heltal delbara med visst heltal
    - Rationella tal som bara innehåller vissa primfaktorer
    - Rotationer i dihedrala grupper, (men inte speglingar, varför?)
    - Rubikskub rotationer av en axel, eller vänder alltid 180*
- Isomorfien utvärderad i delgrupp är delgrupp, strukturen bevaras
- Visa att det inte finns några delgrupper bland:
    - Heltal modulo p, kan man då härleda för andra?
    - 

+ Multiplicera element med delmängd
- Exempel:
    - Kongruensklasser
    - Flytta en linje R^2 under addition
    - Speglade rotationer


- Vad krävs för att sidoklasser av delgrupper ska bli en grupp?
- Hitta några normala delgrupper
    - Visa att kernel alltid är normal, kan alltså kvota bort den


## Lektion 4: Lagranges teorem
Målet är att deltagarna ska bevisa Lagranges teorem (storlek på ändlig grupp delas av storlek på delgrupp), då det är ett väldigt coolt och ganska intutivt koncept som är användbart på många platser. De får även applicera det på bland annat Eulers sat i talteorin

+ Motiverande problem: Bevis av Eulers sats

+ Delgrupp är en grupp inom en annan grupp
+ Exempelvis jämna heltal under addition, rotationer i dihedral grupper

+ Formulera Lagranges Teorem
+ Motivera intuition
+ Målet är att deltagarna ska bevisa denna (och sedan applicera den)

- Bevisa Lagranges Teorem
    - Finns alla element i någon sidoklass till en delgrupp?
    - När är två "representationer" av sidoklasser samma sidoklass?
    - Kan två sidoklasser dela exakt två element? Vilka antal element kan de dela?
    - Med hjälp av ovanstående, bevisa Lagranges teorem

- Applikationer
    - Bevisa Fermats sats för grupper (viss beskrivning av cyklisk grupp innan)
    - Bevisa Eulers sats med hjälp av Lagranges teorem
    - Visa att om två grupper har relativt prima storlekar så är snittet identitetselementet
    - Andra fina applikationer... osäker på exakt vilka

- Kluring frågor utöver
    - Är mängden sidoklasser en grupp? Annars, vad skulle vi kunna ställa för krav på delmängden för att det ska bli det?
    - Några frågor om normala grupper, och kvotgrupper









## Tankar:
- Vore kul med några återkommande exempel:
    - Dihedrala gruppen
    - Rubikskub
    - Heltal under addition
