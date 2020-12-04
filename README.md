# CV #

V dokumentu navajam IT projekte, ki sem jih v glavnem sproduciral sam. Pri nekaterih je šlo za sodelovanje z drugim podjetjem, tam je to izrecno navedeno.
Projekti so navedeni v približnem vrstnem redu, od najbolj svežega do najstarejšega.

## PAMETNI DOMOFON ##
![alt Flutter](icons/flutter.png) ![alt MQTT](icons/mqtt.png) ![alt Arduino](icons/arduino.png) ![alt RPI](icons/raspberry.png) ![alt WEBRTC](icons/webrtc.png)

Projekt je nastal zaradi potrebe po domačem domofonu. Trg ponuja sorazmerno slabo izbiro, kar pa približno ustreza zahtevam pa ima sorazmerno visoko ceno (npr. Doorbird ca 700€). Zaradi tega je nastal kompleten produkt, ki zelo dobro opravlja svojo funkcijo.
 
![alt Doorbell](doorbell.jpg) ![alt Flutter App](doorbell2.png) ![alt Flutter App](doorbell3.png)



## REGISTRACIJA DELOVNEGA ČASA EVIDENTIK ##
![alt PHP](icons/php.png) ![alt RPI](icons/raspberry.png) ![alt WEBRTC](icons/lazarus.png)

Projekt je izveden po naročilu stranke. Gre za celotno okolje za beleženje delovnega časa.  
Registratorji so fizične konzole na osnovi RaspberryPi, ki pošiljajo podatke na strežnik, kjer PHP aplikacija upravlja z izračuni, prikazi, izpisi, obračuni za plače.  
Aplikacija na RPI je bila narejena v Lazarusu oz. FreePascalu, z možnost cross-platform compiliranja tudi na Windows, Android,...  

![alt EvidentikConsole](evidentik1.jpg) ![alt EvidentikWeb](evidentik2.png)



## ARHINT INTRANET SISTEM ##
![alt PHP](icons/php.png) ![alt WEBRTC](icons/lazarus.png) ![alt Exchange](icons/exchange.png) ![alt IdToken](icons/idtoken.png)

Intranet sistem za CRM, izdane račune, potne naloge, opravila, dokumentni sistem in finančno poslovanje podjetja.  
Portal vključuje MS Exchange server sinhronizacijo na osnovi projekta Sinchroton, ki skrbi za sinhronizacijo kontaktov in opravil s pametnimi telefoni.  
Z vidika finančnega poslovanja vključuje PHP davčno potrjevanje, ESLOG elektronsko podpisovanje, izvoz ESLOG 1.6 in 2.0 in izvoz SEPA XML.  
Posebnost poslovanja z računi je, da je vključeno podpisovanje računov s client certifikatom v brskalniku s komponento idTokenSigning.  
Dokumentno poslovanje vključuje skeniranje prejete pošte neposredno iz spletne strani preko Websocketov in lokalne aplikacije za skeniranje (websocket server) napisane v Lazarus.  

![alt Arhint1](arhint2.png) ![alt Arhint2](arhint4.png)
