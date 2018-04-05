<!-- TITLE: Koppelingen -->


# Koppeling met je Google Account
Onder het kopje Integratie bij instellingen kan jij je Google account koppelen. Dit doe je door middel van deze button:
![Integratie](/uploads/integratie.png "Integratie")
Hier schakel je ook gelijk call tracking in of uit.



# Koppeling met je Google Tag Manager Account
Ook kan je het Google Tag Manager Account koppelen. Op die manier kan je eenvoudig het qooqie script plaatsen met onze handige tool.
![Account Koppelen](/uploads/account-koppelen.png "Account Koppelen")
Als je hier op klikt krijg je een pop-up en kan je het tagmanager account koppelen. Je moet nog wel het script kopiëren en plakken in je Google Tag Manager account.

Het script dat op je website komt, vind je terug bij de Integratie onder instellingen. Het script dat je dient te plakken in je website ziet er als volgt uit:
```
<script>
    var _qooqie = _qooqie || {};
    _qooqie['subtenant_id'] = KLANT_ID;
    _qooqie['api_url'] = 'https://api.qooqie.com';
    (function() {
        var q   = document.createElement('script');
        q.type  = 'text/javascript'; q.async = true;
        q.src   = 'https://api.qooqie.com/bundle';
        var s   = document.getElementsByTagName('script')[0];
        s.parentNode.insertBefore(q, s);
    })();
</script>
```

Vervolgens zoekt het script op jouw website de telefoonnummers die vervangen moeten worden. De telefoonnummers die als doorschakelnummer in het qooqie systeem staan, worden door het script opgezocht. Deze worden automatisch vervangen door een uniek traceerbaar telefoonnummer. Het is ook mogelijk om het zelf te doen als je geen Google Tag Manager gebruikt. Gebruik je geen Tag Manager? Kijk dan onder het kopje "integratie zonder Google Tag Manager" en volg die stappen. 



# Koppeling met Google AdWords
Door het koppelen van je Google Account kan je ook je Google AdWords campagnes koppelen met het qooqie account. 
Je selecteert de AdWords accounts die je wilt gebruiken voor dynamische call tracking. Dit ziet er als volgt uit:
![Adwords](/uploads/adwords.png "Adwords")                                  ![Adwords 2](/uploads/adwords-2.png "Adwords 2")

Als je de accounts hebt geselecteerd kan je deze synchroniseren. Aan de linkerkant in het menu zie je dan een kopje Google verschijnen en daar worden jouw lopende AdWords campagnes in teruggeschoten. Zo hoef je niet opnieuw handmatig al je campagnes in te voeren. De telefoonnummers van qooqie die aan AdWords gekoppeld worden zijn dynamisch. 



# Integratie zonder Google Tag Manager
Als je geen Google Tag Manager gebruikt of het zelf wilt doen, kan je ook integreren zonder een Tag Manager account. Daarvoor zijn de volgende stappen vereist:

- Kopieer het script en plak deze in je website na de opende body tag.
```
<script>
    var _qooqie = _qooqie || {};
    _qooqie['subtenant_id'] = KLANT_ID;
    _qooqie['api_url'] = 'https://api.qooqie.com';
    (function() {
        var q   = document.createElement('script');
        q.type  = 'text/javascript'; q.async = true;
        q.src   = 'https://api.qooqie.com/bundle';
        var s   = document.getElementsByTagName('script')[0];
        s.parentNode.insertBefore(q, s);
    })();
</script>
```
Vergeet niet om automatisch nummers vervangen aan te zetten!

Het script heeft de mogelijkheid om automatisch telefoonnummers op je website(s) te herkennen. Wanneer je de functie inschakeld en het script een van je doorschakelnummers herkent, zal er automatisch een qooqie nummer worden geplaatst ter vervanging van het gevonden standaard telefoonnummer. 

# Handmatig nummers aanpassen
Wil je toch liever zelf controle houden over de telefoonnummers die vervangen moeten worden? Dan moet je de volgende stappen ondernemen:

- Alle telefoonnummers die je wilt vervangen met een dynamisch qooqie nummer dien je te omhullen met een element naar keuze met het attribuut: class="qooqie-number-placeholder".
![Span](/uploads/span.png "Span")


# Informeren van de webbeheerder
Als jij de website in beheer hebt van een webbeheerder, is het mogelijk om door hem of haar de integratie te laten doen.
![Informeer](/uploads/informeer.png "Informeer")
Als je klikt op informeer webbeheerder krijg je een pop-up waarin je het email-adres en het domein voor integratie opgeeft. Zo krijgt je webbeheerder de benodigde informatie.


# API koppelingen


