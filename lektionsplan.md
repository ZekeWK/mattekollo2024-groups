# Lektionsplan Gruppteori
(+ är genomgång, - är problem eller bevis deltagarna gör, vid motiverande problem får de försöka lösa men efter några minuter börjar genomgången)

Målet jag tänker med kursen som helhet är att ge grupper som ett verktyg att förklara fenomen med, få se och bevisa några centrala satser, och bekanta deltagarna lite med abstrakt algebra.

Kursen skulle kunna vara strukturerad ungefär:
1. Introduktion till grupper med exempel och kopplade problem
2. Bevisa Lagrange teorem
3. Gruppverkan & bevisa Burnsides lemma
4. Utrymme för fortsättning från tidigare, annar homomorphismer mellan grupper

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

## Lektion 4: Catch up, eller homomorphismer
Målet med den här lektion är att ge lite uttrymme för om något behövs från de tidigare. Om det behövs mer material tänker jag att man arbetar med homomorphismer mellan grupper, men detaljerna är lite oklara.

- Motiverande problem: Finns det någon egentlig skillnad mellan (Q, +) och (Q\{0}, *)? Alltså, kan man tänka sig att de beter sig på samma sätt?
- Definition av homomorphismer, epimorphismer, monomorphismer, och isomorphismer
- Ge olika exempel
- En samling problem om att hitta kluriga sådana mella olika saker grupper, typ:
    - Epimorphism från heltal till cyklisk grupp
    - Monomorphism från heltal till jämna (under addition)
    - Från Z^\infty + till rationella tal under multiplikation
    - Cyklisk till andra cykliska eller sig själv
- En samling om att visa att ingen isomorphi kan finnas:
    - Motiverande problemet
    - Dihedral till cyklisk
- Annat som är kopplat?
- Andra kluriga problem från hela kursen?
- Tänker att det lämnas lite fritt för vad man märker är bra under kursens gång.
