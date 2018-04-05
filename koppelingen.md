<!-- TITLE: Koppelingen -->


# Koppeling met je Google Account
Onder het kopje Integratie bij instellingen kan jij je Google account koppelen. Dit doe je door middel van deze button:
![Integratie](/uploads/integratie.png "Integratie")
Hier schakel je ook gelijk call tracking in of uit.
# Koppeling met je Google Tag Manager Account
Ook kan je het Google Tag Manager Account koppelen. Op die manier kan je eenvoudig het qooqie script plaatsen met onze handige tool.
![Account Koppelen](/uploads/account-koppelen.png "Account Koppelen")
Als je hier op klikt krijg je een pop-up en kan je het tagmanager account koppelen. Je moet nog wel het script kopiëren en plakken in je Google Tag Manager account.

Het script dat je dient te plakken in je website is dit script:
```
<script>
    var _qooqie = _qooqie || {};
    _qooqie['subtenant_id'] = 143;
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
# Koppeling met Google AdWords























