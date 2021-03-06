<!-- TITLE: Algemeen -->
# Realtime dashboard
Middels een overzichtelijk dashboard monitor je realtime de prestaties van al je marketingkanalen. Per kanaal wordt er onder andere inzichtelijk gemaakt wie er heeft gebeld, hoe lang het gesprek heeft geduurd en welk keyword heeft geleid tot een lead. Qooqie call tracking maakt inzichtelijk hoeveel rendement je marketing investering oplevert.
# Wat is een sessie
Een sessie start op het moment dat een bezoeker op jouw website komt en eindigt zodra deze bezoeker jouw website verlaat. Ook het schakelen tussen sub pagina’s op jouw website behoort tot de sessie. 
# Wat is een lead
Zodra iemand op jouw website komt, start er een sessie. Pakt deze bezoeker ook daadwerkelijk de telefoon op en belt dan wordt deze sessie omgezet naar een lead. In de inbox zie je dan onder het kopje “leads” de telefoonnummers waarmee gebeld is naar jouw bedrijf. Hierbij zie je ook de beoordeling van het gesprek. 
# KvK nummer
Het aanmaken van een qooqie account gaat op basis van het KvK-nummer van je bedrijf. Het is niet mogelijk om na het aanmelden je KvK nummer te wijzigen. Dit omdat het account opgebouwd is vanuit het KvK nummer. Wil je deze toch wijzigen? Neem dan contact op met onze klantenservice 085 - 0199 999.
# Terugzien in Google Analytics
In Google Analytics wordt er een event aangemaakt op het moment dat er een qooqie conversie plaatsvindt. 
# Resultaat tot op het zoekwoord (AdWords)
Doordat er aan jouw AdWords advertentie dynamische telefoonnummers gekoppeld worden, is het mogelijk om te achterhalen welke zoekwoorden een bezoeker van jouw website heeft gebruikt. Zo weet je welke zoekwoorden resultaat opleveren en welke minder succesvol zijn.
# AdWords conversie
Het is mogelijk om automatisch een conversie in AdWords aan te maken aan de hand van de duur van een gesprek (minimaal aantal seconden). Standaard staat deze waarde ingesteld op 60 seconden. 
# Dynamisch nummer
Iedere bezoeker die op jouw website komt, krijgt een eigen uniek telefoonnummer te zien op de website. Hierdoor wordt het inzichtelijk voor jouw bedrijf via welke verkeersbron en zelfs via welk zoekwoord de bezoeker op jouw website is gekomen. 
# Vast nummer
Een vast nummer wordt uitgegeven voor een campagne waarbij er maar één nummer nodig is om te kunnen meten. Dit kan bijvoorbeeld een flyer- of een brochure campagne zijn. 
# On-site meten
Door middel van dynamisch gegenereerde telefoonnummers kan jij op je website meten waar de inkomende telefoontjes vandaan komen.
# Off-site meten
Door speciaal gegenereerde nummers kun jij ook al je andere campagnes meten, bijvoorbeeld vanuit de krant of een flyer. 
In het dashboard voeg je een nieuwe campagne toe en geef aan dat je een off-site campagne gaat meten. Bijvoorbeeld print, radio of televisie. Vul de rest van de gegevens in en er zal een uniek traceerbaar telefoonnummer gegenereerd worden. Zo kan je ook off-site meten.
# Ik heb meerdere vestigingen, maar wil er maar 1 meten.
Ja, het is mogelijk om met qooqie call tracking maar één van je vestigingen meten. Heb jij bijvoorbeeld meerdere vestigingen en maar voor één vestiging een campagne? Met het attribuut: class=”qooqie-priority-number-placeholder” kun je dit instellen. Op de plekken waar je call tracking wil, plaats je dat spannertje. Op basis van de campagne en de gekoppelde vestiging wordt er een van de dynamische nummers op deze plek getoond.
# Het vervangen van nummers op je website
Het vervangen van nummers wordt automatisch gedaan door het script zodra deze op je website staat. Het script herkent namelijk de telefoonnummers. Als je de functie inschakelt, dan gaat het script op je website op zoek naar de doorschakelnummers die jij hebt ingegeven bij het qooqie dashboard. Vervolgens vervangt het script deze nummers in een qooqie call tracking nummer. 

Het is ook mogelijk om met een spannertje zelf te kiezen welke telefoonnummers er vervangen dienen te worden op de website. Alle telefoonnummers die je wilt vervangen met een dynamisch qooqie nummer dien je te omhullen met een element naar keuze met het attribuut: class="qooqie-number-placeholder".
# Wat moet je controleren als qooqie call tracking niet werkt op je website?
Als qooqie call tracking niet werkt op je website dien je een aantal facetten na te gaan. Dit zijn:

- De verificatie van het domein. Kijk of de verificatie van het domein goed is gegaan. Ga bij instellingen naar het tabblad "domein". Hier kan je zien of het script goed is geïmplementeerd op je website. Als dit niet geval is, ligt dat aan de plaatsing van het script of aan de overeenkomst tussen de nummers op de website en de doorschakelnummers.
- Staat het script op de juiste plaats? Kijk bij instellingen onder integratie waar je het script moet plaatsen. Het script plak je onder de opende body tag.
- Komen de doorschakelnummers overeen met de nummers op je website? Als deze niet overeen komen, kan het script van qooqie niet de nummers herkennen.
- Track je meerdere vestigingen? Kijk of het spannertje op de juiste plek staat om het telefoonnummer heen. De juiste wijze is als volgt:
```
<span class="qooqie-priority-number-placeholder"> TEL. NUMMER </span>
```