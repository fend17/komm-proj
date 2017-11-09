# User Stories

Allting man utvecklar gör man för en anledning men det är inte helt tydligt för samtliga **vem** en gör någonting för, **varför** en gör det samt **vad** det är som ska göras.

För att få en gemensam förståelse används ofta **User Stories** där man försöker frångå att skriva allt för tekniska krav och istället fokuserar på att skapa en gemensam förståelse för vad som ska uppnås:

* “Som persona
    * Vem eller vilka riktar vi oss till: den som ska underhålla systemet, den som ska använda systemet. Som operatör eller som privatperson. Definiera vem det är vi riktar oss till
* “Vill jag"
    * Vad är avsikten och vad är målet? Försök att frångå "Vill jag ha ett inputfält och en knapp kopplat till det inputfältet som lagrar mitt värde", utan gå mot att mer övergripande förklara: "Vill jag kunna lägga till ett nytt inlägg" så att även mindre tekniskt insatta skulle kunna förstå.
* “Därför att/så”
    * Varför vill personen göra detta? Vad är anledningen? Kan vara svårt att definiera exakt men någon anledning finns det alltid för att något finns i en applikation, även om det inte är en bra anledning.

**Exempel**: Som användare vill jag ha ett kommentarsfält så att jag kan dela med min av mina åsikter och ge feedback.

## Övning

Använd kravspecifikationen nedan, främst **Tekniska krav** och utforma **User Stories** baserade på dessa krav. 

Skriv upp alla **user stories** i valfritt dokument.


## Kravspecifikation
>Bloggsystem

### Projektets syfte
Vi på Millhouse vill ha ett enklare bloggsystem där användaren kan logga in, skapa inlägg samt kommentera på på dessa inlägg. Kopplat till detta ska man även kunna sortera dessa inlägg baserat på datum de är skapade samt vilken kategori de tillhör. Systemet ska ha ett lättanvänt gränssnitt och rikta sig till personer med låg datorvana.

### Företaget Millhouse
Millhouse är ett grossistföretag som säljer kläder, accesoarer och mindre inredningsartiklar till mode- och livsstilsbutiker. Millhouse planerar nu att starta en rad egna webbshopar med produkttyperna:
- klockor
- solglasögon
- mindre inredningsartiklar

För att skapa dialog med slutkund vill de skapa en blogg där kunderna kan kommentera, komma med önskemål med mera. Det är denna del man önskar köpa in från ett mindre bolag. Millhouse omsätter 75 miljoner kronor årligen och har 50 anställda, främst inom administration, inköp och lagerhantering.

## Tekniska krav
* Bloggen ska kunna ha ett obegränsat antal inlägg (produkter).
* Det ska finnas tre olika användare: administratör, anställd på företaget samt kommentator. Kommentatorn ska bara kunna kommentera medan den anställda kan lägga upp nya produkter och redigera sina egna produkter. Administratören kan ändra på allt.
* Ett inlägg ska bestå av rubrik, skapat på datum, text relaterat till produkten, bild på produkt, tänkt pris, författarens namn samt författarens e-post.
* När man kommer till sidan så ska de senaste produkterna visas upp.
* Varje inlägg ska kunna tillhöra en specifik kategori.
* En besökare på sidan ska kunna visa enbart inlägg inom en viss kategori.
* Som oinloggad ska man kunna se produkterna på förstasidan.
* Under varje produkt ska det dessutom finnas en länk som lyder "kommentera". När man klickar på länken ska man komma till en sida som visar inlägget man vill kommentera samt ett kommentarsformulär.
