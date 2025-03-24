# Projekt i grupp
#### Front-end 2024/2025

## Övergripande om arbetet
1. Uppgiften kommer att löpa över 3 veckor.  
2. Varje vecka innehåller en sprint. 
3. Varje sprint innehåller olika delmål och vem som är ansvarig för dem.
4. En sprint avslutas med kodgranskning på fredagen, där ni presenterar och granskar varandras kod inom gruppen.  
5. Efter kodgranskningen sätts nya delmål och ansvar inom dessa. 
6. Utvärdering av arbetet

## Arbetsflöde GitHub 

Gruppens arbete utgår från en branch på GitHub. Det kan vara en main branch eller en dev branch. (Om man vill ha en dev branch blir det ytterligare ett steg bara. Det är vanligt om man vill ha en live version men också en dev branch där man kan testa innan man lägger ut live/production). 

1. Varje delmål ges en egen branch som den eller de som arbetar med det målet arbetar i. 
2. I denna branch gör ansvarig löpande commits med tydliga beskrivningar som synkas kontinuerligt så att all kod finns tillgänglig även om man blir sjuk eller dylikt.  
3. När koden för delmoment är klar gör man en pull request. Denna granskas sedan av gruppen och mergas in i den branch man arbetar utifrån.
4. Ibland behöver något fixas i koden och då fortsätter ansvarig att arbeta med den och gör en ny pull request när det är klart.

Mindre delmål och akuta buggfixar kan göras löpande i veckan på samma sätt, men i par om ni inte hinner ses hela gruppen. 


## Appen
### Grundkrav
Den app ni gör ska hantera och innehålla följande som minimikrav:
1. Appen ska vara gjord med Next.js App router
2. Använda data från dummyJSON API (products, recipes eller posts)
3. Hämta data med fetch() från flera endpoints (t ex alla produkter och produkt via id)
4. Innehålla minst 2 olika statiska routes och minst 1 dynamisk där lämplig data visas
5. Ha en navigation där man kan ta sig till de olika sidorna
6. Innehålla någon form av interaktiva element som t ex sök, filter, sortering, paginering
7. Ska vara designad med tillgänglighet i åtanke (använd t ex WAVE för att kontrollera)
8. Ska vara responsiv och ha en god design både på mindre och större skärmar
9. Använda antingen CSS Modules eller Tailwind CSS för formgivning (+ ev andra bibliotek som shadcn och Lucide)

[Skissförslag i figma](https://www.figma.com/design/w65AsmJZbRa76UlV99mLsA/Grupprojekt%2C-skissf%C3%B6rslag?node-id=0-1&p=f&t=JSSjmNNll1WORcbx-0)


## Extra om ni har tid
När ni är klara med grundkraven kan ni bygga på med ytterligare funktionalitet. Detta är valfritt och nedanstående är endast exempel och inspiration.

1. Använd en useContext för att skapa en varukorg, dark/light-theme, inloggning (kan vara fake men bara så användaren sparas tillfälligt) eller spara receptfavoriter
2. Använd loading.tsx eller suspense tillsammans med skeletons eller loading spinners för att visa när saker laddas
3. Lägg till mer interaktivitet eller gör kombinationer av dessa. T ex sök + paginering eller välja kategori och sortering samtidigt.  
4. Gör ett formulär för anmälan till nyhetsbrev
5. Gör en hamburgermeny som visas på små skärmar
6. Gör en deployment av appen på t ex Vercel (med GitHub actions om ni vill)


## Utvärdering
När projektet är klart skriver ni en utvärdering av arbetet där ni reflekterar över er egen del i projektet. Detta skriver ni antingen i er lärarchatt eller i ett dokument som ni e-postar till oss lärare. 

Besvara följande:
1. Beskriv 2-3 delar av koden som du är extra nöjd med. Vad är du nöjd med i den, vilka val gjorde du och varför? (kopiera gärna in kodbitar eller hänvisa till koden på github med sida/rad).
2. Beskriv något som du inte lyckades få till som du ville och varför.
3. Vad var den största utmaningen i projektet och hur hanterade du det?
4. Vad tänker du att du skulle behöva lära dig mer om när du tänker tillbaka på arbetet ni utfört?
5. Hur följde ni Scrum under arbetet?



 

 


